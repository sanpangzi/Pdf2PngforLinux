# Pdf2PngforWindows
这是一个nodejs库，运行环境是linux,如果你想运行在windows上，<br>
请参考：https://github.com/sanpangzi/Pdf2PngforWindows<br>
本库可以在Linux下，可以把一个多页的pdf转成多页png图片
# 怎么使用这个库？
  1. 首先下载到本地任意文件夹，使用之前，确保已安装npm,nodejs<br>
  2. 进入下载后的文件夹，比如：/usr/local/pdftopngforLinux<br>
     进入之后，运行： npm install<br>
     这个命令，会安装所需的两个模块tmp及filesource<br>
  3. 安装完以上两个模块，就可以运行测试了，测试命令如下：<br>
      node convert.js<br>
      不出意外的话，你会看到test文件夹下，有4张图片，分别是1.png  2.png  3.png  4.png<br>
 # 注意点
  1.本代码是借助Ghostscript实现的，这个Ghostscript需要预先安装，安装方法如下：<br>
     sudo apt-get update<br>
     sudo apt-get install ghostscript<br>
  2. 本文参考的是https://www.npmjs.com/package/pdf2png,
     有兴趣的话，可以看看原版。<br>
  3. 有任何问题，可以在issues中提，也可以联系我，QQ：3207740041<br>
