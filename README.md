<h2 align="center"> 北京邮电大学信息与通信工程学院选课参考指南 </h2>
<p align="center"><b>专业选修课/英语选修课/体育选修课/公共选修课/课程设计/其他</b></p>
<p align="center"><b>投稿链接：https://www.wjx.cn/vj/wGw4GYE.aspx</b></p>

<p align="center">
    <img src="https://badgen.net/github/license/lgc0208/course_reference_SICE_BUPT/">
    <img src="https://badgen.net/github/checks/lgc0208/course_reference_SICE_BUPT/main/">
    <img src="https://badgen.net/github/commits/lgc0208/course_reference_SICE_BUPT/main/">
    <img src="https://badgen.net/github/stars/lgc0208/course_reference_SICE_BUPT">
    <img src="https://badgen.net/github/last-commit/lgc0208/course_reference_SICE_BUPT/main/">
</p>


## 目录

- [目录结构描述](#目录结构描述)
- [使用说明](#使用说明)
  - [只想检索数据](#只想检索数据)
  - [想要获取原始数据](#想要获取原始数据)
- [UI 界面](#UI-界面)
- [数据更新](#数据更新)


## 目录结构描述

```
├── README.md                  // help
├── index.html                 // 网页端代码
├── data.js 	        	   // 评价数据
└── figure                     // 背景图片库
    ├── 45degreee_fabric.png   // 灰色背景
    ├── blue-snow.png          // 蓝色雪花背景
    ├── jiaran.jpg             // 卡通少女背景
    ├── jr.jpg                 // 卡通少女背景
    └── watercolor.png 	       // 粉色花瓣背景

```

## 使用说明

### 只想检索数据

1. 解析网址：www.xtxkzn.ml
2. Github Page 网址（备用）：https://lgc0208.github.io/course_reference_SICE_BUPT/
3. 下载文件后，使用浏览器打开 `index.html` 文件（此时最好保持联网状态，因为代码里使用了`bootstrap`和`jquery`，不联网可能 UI 会很乱）


### 想要获取原始数据

- `data.js` 文件中储存了原始数据，初始数据来自于2021年年底信通院18级 ZJR 同学创建的共享文档。后续数据来自于使用问卷星征集到的投稿。投稿链接：https://www.wjx.cn/vj/wGw4GYE.aspx
- 数据开源存储，不排除可能因为不可抗力因素关闭本平台
- `data.js` 中的数据格式为
```
[
  {
    "course_type": "", 
    "course": "", 
    "teacher": "", 
    "score": "", 
    "description": ""
  }
]
```

## UI 界面

`index.html`是使用`bootstrap`和`jquery`完成的简易的检索页面，页面所需要的数据存储在`data.js`中，页面背景存储在 `figure` 文件夹中。初始背景为 `figure/blue_snow.png`

## 数据更新

在非选课期间，数据更新频率会保持在半个月至一个月一次。在选课期间，数据更新频率会保持在一天两次。也可以通过该项目的issue催更

为了便于管理，请统一使用投稿链接：https://www.wjx.cn/vj/wGw4GYE.aspx 进行投稿。问卷星收集到的问卷完全匿名，请尽量客观。对于具有明显人身攻击的投稿无法进行更新，请您见谅

**祝大家都能选到轻松愉悦分还高的选修课！**
