cartool
=======

Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.

1、首先解压ipa包，得到.car资源包

2、下载 cartool 到本地
运行可知需要传入一个文件路径和解压后的文件输出路径；
选择Edit Scheme
<p align="center" >
  <img src="https://github.com/webersongao/cartool/blob/master/001.png" alt="Cartool" title="Cartool">
</p>
大概看下源码可以知道，第一个是需要解压的文件路径，第二个参数是解压后的文件路径。

2、结果与注意

在桌面创建好对应的解压文件夹（CartoolPath）在cmd + R 后就可以看到图片了。

注意路径中不要有空格和中文，不然可能有问题
