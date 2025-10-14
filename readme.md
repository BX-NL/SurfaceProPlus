# SurfaceProPlus

## 介绍 Info

让Surface再次伟大！

Make Surface Great Again!

给Surface做的一个工具箱。

A toolbox for Surface.

包含了一堆有用或者没用的小功能和工具。

Include some useful or unuseful little features and tools.

可自定义添加功能和工具。

Allow user to add custom features and tools.

>Base on: Python, Shell, Kivy, win32API, PyQT

---

## 功能 Module

1.仪表盘

1.Dashboard

显示设备信息，显示性能占用等

Show infos of Surface, CPU used, memory used and etc.

可能有现成的模块，尝试接入。

Maybe there were some packages, try to connect it.

>Base on: Python, win32API, PyQt

2.屏幕手柄

2.Screen Gamepad

屏幕触控手柄，模拟XBOX手柄。

Touch screen gamepad, to simulate a XBOX Controler.

>Base on: Python, Kivy, vgamepad, Xinput

3.OBS网页推流

3.OBS To Website

OBS采集屏幕画面推流到网页中

Use OBS to capture the screen and push to website.

>Base on: Python, FastAPI, OBS, HTML, JavaScript, CSS, M3U8?

4.结束进程（用于Surface Book）

4.Process Killer(Work for Surface Book)

~~可能用不上，先留个坑位~~

~~It maybe useless, new a package to hold on.~~

结束占用了独显的进程，便于分离或者别的什么需求。

Kill process which is using discrete graphics card, use to separate the screen or others.

>Base on: Python, win32API

5.快捷翻译

5.Quick translation

使用快捷键自动复制选中的文本并翻译为目标语言，发送Windows通知并将结果塞到剪贴板里。

Use hotkey to automatically copy text which is select and translation to target language, then send a Windows notice and copy the result to the clipboard.

>有[TinyTranslator](https://github.com/BX-NL/TinyTranslator)在，需要研究一下触控笔怎么接入使用。

>There is [TinyTranslator](https://github.com/BX-NL/TinyTranslator), I need to try to use the surface pen.

>把现有的main包成接口，直接运行时执行一遍，开另一个当快捷键模式。

>Build the main into API, run one time when run, run another program to use listen hotkey mode.

>Base on: Python, Shell

0.其它乱七八糟的东西

0.Other things

小工具

塞一点可能用得上的工具软件，以及自定义功能。

Add some probably useful tools, softwares, and custom features.

友情链接

Friendly Link

>Mykeymap

>屏幕触控手势

>尝试接入官方的Surface程序(连到仪表盘?)

---

## Link

[SurfaceProPlus](https://github.com/BX-NL/SurfaceProPlus)
[TinyTranslator](https://github.com/BX-NL/TinyTranslator)