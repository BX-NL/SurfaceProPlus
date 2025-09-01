# SurfaceProPlus

## 介绍 Info

让Surface再次伟大！

Make Surface Great Again!

给Surface做的一个工具箱。

A toolbox for Surface.

包含了一堆有用或者没用的小功能和工具。

Include some useful or unuseful little features and tools.

可自定义添加功能。

Allow add other features and tools.

>Base on: Python, Shell, PyQT, Kivy, win32API

---

## Todo

1.仪表盘

1.Dashboard

显示设备信息，显示性能占用等

Show infos of Surface, CPU used, memory used and etc.

可能有现成的模块，尝试接入。

Maybe there are some packages, try to connect it.

>Base on: Python, win32API, PyQt

2.屏幕手柄

2.Screen Gamepad

屏幕触控手柄，模拟XBOX手柄。

Touch screen gamepad, to simulate a XBOX Controler.

>Base on: Python, Kivy, vgamepad, Xinput

3.OBS网页推流

3.OBS To Website

OBS采集屏幕画面推流到网页中

Use OBS to capture screen and push to website.

>Base on: Python, FastAPI, OBS, HTML, JavaScript, CSS, M3U8?

4.结束进程（用于Surface Book）

4.Process Killer(Work for Surface Book)

~~可能用不上，先留个坑位~~

~~Maybe useless, new a package to hold on first.~~

结束占用了独显的进程，便于分离或者别的什么需求。

Kill process that is using discrete graphics card, use to separate the screen or others.

>Base on: Python, win32API

5.快捷翻译

5.Quick translation

使用快捷键自动复制选中文本并翻译，使用Windows发送通知并将结果塞到剪贴板里。

Use hotkey to automatically copy text which select and translation, then send a Windows notice and copy the result to the clipboard.

>有[TinyTranslator](https://github.com/BX-NL/TinyTranslator)在，需要研究一下触控笔怎么用。

>There is [TinyTranslator](https://github.com/BX-NL/TinyTranslator), I need to try how to use the surface pen.

>把main包成接口，直接运行时执行，快捷键模式开另一个。

>Build main into API, run when run, run another program to listen hotkey.

>Base on: Python, Shell

0.其它乱七八糟的东西

0.Others

塞一点可能用得上的工具软件，以及自定义功能。

Add some tools that are probably useful, and custom features.

---

## Link

[SurfaceProPlus](https://github.com/BX-NL/SurfaceProPlus)
[TinyTranslator](https://github.com/BX-NL/TinyTranslator)