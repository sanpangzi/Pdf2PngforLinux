# Pdf2PngforLinux
这是一个Nodejs库，支持linux下pdf转png.
# 第一步要在linux上安装npm,nodejs
可以参考官网上的安装
# 第二步要在linux上安装Ghostscript
我给出一种ubuntu上全局安装的方法，如下：<br>
sudo apt-get update<br>
sudo apt-get install ghostscript<br>
# 第三步要在linux上安装tmp模块
  首先进入你下载本库文件的文件夹，之后，运行如下命令:<br>
  npm install tmp -save <br>
# 第四步要在linux上安装filesource模块
  首先进入你下载本库文件的文件夹，之后，运行如下命令:<br>
  npm install filesource -save
# 第五步要在linux上运行测试
  首先进入你下载本库文件的文件夹，之后，运行如下命令:<br>
   node convert.js <br>
   之后，在test文件夹中，你将看到4张图片，对应pdf的第1，2，3，4页。<br>
