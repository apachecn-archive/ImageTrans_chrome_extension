# ImageTrans_chrome_extension

Chrome Extension for ImageTrans. You can use this to translate images on webpages.

It should be used in couple with [ImageTrans](https://www.basiccat.org/imagetrans) and [ImageTrans_wsServer](https://github.com/xulihang/ImageTrans_wsServer).

## Chrome Version

The plugin does not work on Chrome >94 as it restricted the requests in secure context. You can download a portable version of Chrome 93 from [here](https://www.yanlutong.com/pcsoft/7106/).

## Installation

1. Install from [Chrome Store](https://chrome.google.com/webstore/detail/imagetrans/lkijcgjookpddgfacoankphnpbinmhia?hl=en) or manually install it by downloading this repository and installing the extension through More Tools->Extensions->Load unpacked. Remember to check developer mode.
2. Purchase ImageTrans and install it.
3. Download [ImageTrans_wsServer.jar](https://github.com/xulihang/ImageTrans_wsServer/releases/download/builds/ImageTrans_wsServer.jar) and put it with ImageTrans.

## Usage

1. Pin the ImageTrans extension.
2. Open ImageTrans. Open Server through Tools->Server. Press Start the server button and press Reconnect button. Check silent translation mode if you want ImageTrans to do tasks silently.
3. Open or create an ImageTrans project. Setup things like its language pair in project setting. Choose params like ocrengine and language.
4. In Chrome, move the mouse over the picture which needs to be translated. Press CTRL+SHIFT+F （CTRL+SHIFT+V on mac） to call the popup and press TAB to alter the buttons. Press Enter to run the desired action like translating the image or getting the image's src.


## Supported Web Sites

If the images on a web site have a unique URL and are downloadable, then the extension can handle it, otherwise, the web site is not supported.

[List of supported sites](./supported-sites.md)

## Video

* Demo video on Youtube: [link](https://www.youtube.com/watch?v=R7pv02jwL_k)
* Tutorial: <https://www.bilibili.com/video/BV1E5411p73K?p=2>


<hr/>

ImageTrans的Chrome扩展程序。你可以用它来翻译网页上的图像。

它需要与[ImageTrans](https://www.basiccat.org/imagetrans)和[ImageTrans_wsServer](https://github.com/xulihang/ImageTrans_wsServer)配合使用。

## Chrome版本说明

Chrome94以上版本会限制从http获取请求。可以从[这里](https://www.yanlutong.com/pcsoft/7106/)下载一个Chrome 93的绿色版。

## 安装

1. 从[商店](https://chrome.google.com/webstore/detail/imagetrans/lkijcgjookpddgfacoankphnpbinmhia?hl=en)安装或者下载这个仓库中的扩展手动安装。手动安装操作：更多工具->扩展程序->加载已解压的扩展程序。记得勾选开发者模式。
2. 购买ImageTrans并安装。
3. 下载[ImageTrans_wsServer.jar](https://github.com/xulihang/ImageTrans_wsServer/releases/download/builds/ImageTrans_wsServer.jar)并将其与ImageTrans放在一起。

## 用法

1. 固定ImageTrans扩展到工具栏。
2. 打开ImageTrans。点击菜单栏->工具->服务器，打开服务器程序。点击“启动服务器”按钮，然后点击“重新连接”按钮。如果希望ImageTrans以静默方式执行任务，勾选静默翻译。
3. 打开或创建一个ImageTrans项目。在项目设置中设置如语言对等项目。选好OCR引擎和语言。
4. 在Chrome中，将鼠标移到需要翻译的图片上。按下CTRL + SHIFT + F（在Mac上为CTRL + SHIFT + V）调出操作窗口，按TAB键更改按钮。按回车键运行所需的操作，比如翻译图像或获取图像的链接。

## 受支持的网站

如果网站的图片有明确的URL并且可以下载，那这个扩展程序就能处理，如果不是的话，这个网站就不受支持。

[支持的网站列表](./supported-sites.md)

## 视频

B站上的演示和教程视频：[链接](https://www.bilibili.com/video/BV1E5411p73K/)



