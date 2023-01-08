# 用开发者工具在TETR.IO得到纯净的导播界面

**如果懒得话可以只选择**[隐藏观战聊天框](#6.隐藏观战聊天框!（可选）)和[隐藏观战栏](#5.隐藏观战栏!（可选）)



## 1.基础工作

打开TETR.IO

等待登录

<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd>调出开发者工具



## 2.隐藏个人信息![](https://s3.bmp.ovh/imgs/2022/07/31/73afd4e58cde76cc.png)（可选)

找到

```html
<div id="menus" class="" data-menu-type="home">
```

点击开头的小三角展开

![](https://i.bmp.ovh/imgs/2022/07/31/796ee622711dd549.png)

然后找到

```html
<div id="header">
```

点击开头的小三角展开

![](https://i.bmp.ovh/imgs/2022/07/31/eacd45393db7cc9a.png)

再然后找到

```html
<div id="me" class="ns" data-hover="tap" data-hit="click">...</div>
```

右键选择Hide element

![](https://s3.bmp.ovh/imgs/2022/07/30/0b1f9135e8edc4f0.png)

## 3.隐藏好友和通知![](https://s3.bmp.ovh/imgs/2022/07/31/acf3a487148bf4c8.png)（可选)

找到

```html
<div id="menus" class="" data-menu-type="home">
```

点击开头的小三角展开

![](https://i.bmp.ovh/imgs/2022/07/31/796ee622711dd549.png)

然后找到

```html
<div id="header">
```

点击开头的小三角展开

![](https://i.bmp.ovh/imgs/2022/07/31/eacd45393db7cc9a.png)

再然后找到

```html
<div id="social_tray" class="ns" data-hover="tap" data-hit="click">...</div>
```

![](https://i.bmp.ovh/imgs/2022/07/31/218eb20f31747bad.png)

右键选择Hide element

## 4.隐藏房间ID![](https://s3.bmp.ovh/imgs/2022/07/31/28ab34d1ede548e3.png)（可选)

**注：CONFIG→VIDEO & INTERFACE把HIDE ROOM IDS打开后的效果和这并不一样**

![](https://s3.bmp.ovh/imgs/2022/07/31/8b28df42a5d313c3.png)

开启后

![](https://s3.bmp.ovh/imgs/2022/07/31/3afc048ea0d220ea.png)

找到

```html
<div id="menus" class="" data-menu-type="home">
```

点击开头的小三角展开

![](https://i.bmp.ovh/imgs/2022/07/31/796ee622711dd549.png)

然后找到

```html
<div id="header">
```

点击开头的小三角展开

![](https://i.bmp.ovh/imgs/2022/07/31/eacd45393db7cc9a.png)

再然后找到

```html
<div id="roomid_container" class="ns" data-hover="tap" data-hit="click">...</div>
```

![](https://i.bmp.ovh/imgs/2022/07/31/e411089072122697.png)

右键选择Hide element

## 5.隐藏观战栏![](https://s3.bmp.ovh/imgs/2022/07/31/b2058e2984f4b575.png)（可选)

找到

```html
<div id="spectate" class="watch_header ns hidden"></div>
```

![](https://i.bmp.ovh/imgs/2022/07/31/4259ced0b6afe9dc.png)

右键选择Hide element

## 6.隐藏观战聊天框![](https://s3.bmp.ovh/imgs/2022/07/31/c0f31b47db0880a4.png)（可选)

**注：建议到CONFIG→VIDEO & INTERFACE把HIDE CHAT WHEN INGAME打开来代替此项**

![](https://s3.bmp.ovh/imgs/2022/07/31/710717995b317961.png)

找到

```html
<div id="ingame_chat_container">...</div>
```

![](https://s3.bmp.ovh/imgs/2022/07/30/870f6f4fc85092fa.png)



右键选择Hide element