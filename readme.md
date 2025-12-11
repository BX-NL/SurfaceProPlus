# SurfaceProPlus

## 介绍 Info

让Surface再次伟大！

Make Surface Great Again!

给Surface做的一个工具箱。

A toolbox for Surface.

包含了一堆有用或者没用的小功能和工具。

Include some useful or unuseful little features and tools.

可自定义添加功能和工具。

Allow users to add custom features and tools.

>Base on: Python, Shell, Kivy, win32API, PyQT

---

## 功能 Module

**1.仪表盘 Dashboard**

显示设备信息，显示性能占用等

Show infos of Surface, CPU used, memory used and etc.

可能有现成的模块，尝试接入。

Maybe there were some packages, try to connect them.

>Base on: Python, win32API, Batchfile, PyQt

**2.屏幕手柄 Screen Gamepad**

屏幕触控手柄，模拟XBOX手柄。

Touch screen gamepad, to simulate a XBOX Controler.

>Base on: Python, Kivy, vgamepad, Xinput

**3.OBS网页推流 OBS To Website**

OBS采集屏幕画面推流到网页中

Use OBS to capture the screen and push to website.

>Base on: Python, FastAPI, OBS, HTML, JavaScript, CSS, M3U8?

**4.结束进程 Process Killer**

用于Surface Book

Work for Surface Book

~~可能用不上，先留个坑位~~

~~It maybe useless, new a package to hold on.~~

结束占用了独显的进程，便于分离或者别的什么需求。

Kill process which is using discrete graphics card, use to separate the screen or others.

>Base on: Python, win32API, os

**5.快捷翻译 Quick translation**

使用快捷键自动复制选中的文本并翻译为目标语言，发送Windows通知并将结果塞到剪贴板里。

Use hotkey to automatically copy text which is select and translate to the target language, then send a Windows notice and copy the result to the clipboard.

>有做好的[TinyTranslator](https://github.com/BX-NL/TinyTranslator)在，需要研究一下触控笔怎么接入使用。

>There is [TinyTranslator](https://github.com/BX-NL/TinyTranslator), I need to try how to use the surface pen.

>把现有的main包成接口，直接运行时执行一遍，开另一个当快捷键模式。

>Build the main into API, run one time when it run, run another program to run listen hotkey mode.

>Base on: Python, Shell, googletrans (and other translate APIs)

**0.其它乱七八糟的东西 Other things**

小工具 Little Tools

>塞一点可能用得上的工具软件，以及自定义功能。

>Add some probably useful tools, software, and custom features.

好用的软件 Useful Software

>键盘映射 Mykeymap

>屏幕触控手势 GestureSign

>>尝试接入官方的Surface程序(连到仪表盘?)

>>Try to connect Surface from offical(Connect to dashboard?)

---

## 链接 Link

**模块链接 Module Link**

[SurfaceProPlus](https://github.com/BX-NL/SurfaceProPlus)

[TinyTranslator](https://github.com/BX-NL/TinyTranslator)

[]()

**友情链接 Friendly Link**

>[Example](https://*.*)

---

## 感谢 Thanks

[碧霄-凝落](https://github.com/BX-NL)
