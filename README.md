# 数据包生成器 <br />Datapack-Generator

一个生成我的世界数据包的**图形化**程序<br />
A **GUI** program to generate a datapack in minecraft

## 框架  Frame
本工具基于Qt框架(PyQt5)
<br>发行版本由<a herf="https://github.com/pyinstaller/pyinstaller">pyinstaller</a>打包<br>
由QtDesigner进行视觉设计

<br />The generator is based on the design of Qt framework and Qt Designer.<br>
The generator is pack by <a herf="https://github.com/pyinstaller/pyinstaller">pyinstaller</a>.

## 使用 How to use

在Releases中找到你想要的版本并找到下载地址（有些版本因故文件没有上传在Github上），下载后双击运行即可。<br>

Find the release you want in Releases and the download address (some versions are not uploaded on Github) , then double-click to run it.<br>

如果你想抢先体验，请在仓库文件夹“All_Verisons”中找到你想要的版本的文件，下载下来并配置好pyqt5环境，双击运行。<br>

If you want to use unreleased version, please find the version you want in the repository folder“All_Versions”, download it, configure the pyqt5 environment, and double-click to run it.

### PyQt5的安装 Installation of PyQt5

打开cmd并运行以下指令：<br>
Open cmd and run the following command:

> pip install PyQt5

如果你在中国或下载速度较慢，请运行如下命令以用清华大学镜像源下载（仅此一次）：
<br>If you are in China or the download speed is slow, please run the following command to download from the Tsinghua University's Mirror(Only this time):

>pip install -i https://pypi.tuna.tsinghua.edu.cn/simple PyQt

或者永久使用镜像源(请确保您的pip版本大于10.0.0):<br>
Or permanently use the mirror source(please make sure that version of your pip greater than or equal to 10.0.0):
<br>如果你看到了以下提示，请检查环境目录，具体操作请百度“python环境目录设置”:

>python -m pip install --upgrade pip
<br>pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple

<br>If you see the following prompt, please check the environment directory. For specific operations, please search "python environment directory settings":
>'pip' 不是内部或外部命令，也不是可运行的程序
或批处理文件。

>'pip' is not an internal or external command, nor is it a runnable program
Or batch file.
## 作者  Auther
By Bi2Nb9O3 & ChenMoM


## Debug 捉虫

这里是调试区，供用户、开发者、贡献者测试新版本

### 如何调试捉虫？
 - 找到对应版本的程序文件（新版本已经将debug版本功能合并进入主版本）
 - 运行程序，一顿操作找到bug
 - 转到[github issue]("https://github.dev/CN-ice-create/Datapack-Generator/issues")
 - 提交issue，格式见#6 issue
