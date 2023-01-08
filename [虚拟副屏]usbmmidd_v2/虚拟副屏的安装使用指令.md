# 虚拟副屏的安装/使用指令

在某些情况下，你可能需要模拟一个或多个连接到系统的副显示器。一般用于远程控制或 USB 类型的显示器，如果你有该需求那这个文档可能对你有用



此文档修改自https://www.amyuni.com/forum/viewtopic.php?t=3030配图来源:[MianSoft](https://github.com/MianSoft)

[TOC]

## 安装部分

### 1.下载所需驱动

在浏览器打开https://www.amyuni.com/downloads/usbmmidd_v2.zip

下载后解压缩到你想要的位置

### 2.安装驱动

来到你解压后的目录，比如说C:\Users\admin\Desktop\MianSoft\usbmmidd_v2

摁住<kbd>Shift</kbd>+<kbd>鼠标右键</kbd>选择"在此处打开Powershell窗口"

[![vlnDCq.png](https://s1.ax1x.com/2022/08/09/vlnDCq.png)](https://imgtu.com/i/vlnDCq)

输入

```
.\deviceinstaller64 install usbmmidd.inf usbmmidd
```

一般会有UAC弹窗，选择"是"即可

[![vlns2V.png](https://s1.ax1x.com/2022/08/09/vlns2V.png)](https://imgtu.com/i/vlns2V)

确定后会弹出一个cmd 窗口来执行，安装完就会消失

### 3.确认驱动安装成功

在任务栏上的"开始"上按<kbd>鼠标右键</kbd>，选择“设备管理器“

[![vln2b4.png](https://s1.ax1x.com/2022/08/09/vln2b4.png)](https://imgtu.com/i/vln2b4)

在设备管理器里找到显示适配器一项后展开，如果有USB Mobile Monitor Virtual Display就是安装成功了

[![vlnfa9.png](https://s1.ax1x.com/2022/08/09/vlnfa9.png)](https://imgtu.com/i/vlnfa9)

## 如何创建/关闭虚拟副屏

来到你解压后的目录，比如说C:\Users\admin\Desktop\MianSoft\usbmmidd_v2

摁住<kbd>Shift</kbd>+<kbd>鼠标右键</kbd>选择"在此处打开Powershell窗口"

[![vlnDCq.png](https://s1.ax1x.com/2022/08/09/vlnDCq.png)](https://imgtu.com/i/vlnDCq)

输入

```
.\deviceinstaller64 enableidd 1
```

一般会有UAC弹窗，选择"是"即可

[![vluaQK.png](https://s1.ax1x.com/2022/08/09/vluaQK.png)](https://imgtu.com/i/vluaQK)

确定后会弹出一个cmd 窗口来执行，创建完就会消失

可以重复输入这个指令来创建多个虚拟副屏最多四次

如果你需要关闭虚拟副屏可以输入

```
.\deviceinstaller64 enableidd 0
```

一般会有UAC弹窗，重复上面的即可
