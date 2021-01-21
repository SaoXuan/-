# -#### 前言

闲来无事，讲一下如何装黑苹果，对于我们学生党，mac算是一个奢侈品，那么我们如何用经济的手段体验高端奢侈的mac系统呢？

#### 工具下载/镜像下载

实在是不知道上传到哪里只能百度云了，如果下载的太慢，欢迎进群索取1065233314（野生程序员）

资源放到公众号平台了，回复 ：**黑苹果** 即可获取！

扫码关注：

![image-20210121173311874](http://blogs-picture.yscxy.net/img/image-20210121173311874.png)

#### 整理要安装mac的磁盘

既然想去用mac系统就需要我们准备相应的空间

- 打开我们的工具文件夹找到DiskGenius_4.7.2_x86打开该软件

![image-20210121173347658](http://blogs-picture.yscxy.net/img/image-20210121173347658.png)

- 选择一块分区，我们右键删除该分区（PS记得把删除的东西进行备份，不然你的资料都没了）然后保存更改。!

![image-20210121173430727](http://blogs-picture.yscxy.net/img/image-20210121173433362.png)

- 找到C盘所在的分区

![image-20210121173453486](http://blogs-picture.yscxy.net/img/image-20210121173453486.png)

- 把我们的clover文件复制进来

![image-20210121173513887](http://blogs-picture.yscxy.net/img/image-20210121173513887.png)

![image-20210121173529784](http://blogs-picture.yscxy.net/img/image-20210121173529784.png)

#### 开始安装恢复镜像

安装并打开工具文件夹中的Paragon Hard Disk Manager™ 12 Server，选择我们刚刚清空的磁盘

![image-20210121173544316](http://blogs-picture.yscxy.net/img/image-20210121173544316.png)

![image-20210121173559216](http://blogs-picture.yscxy.net/img/image-20210121173559216.png)

![image-20210121173620816](http://blogs-picture.yscxy.net/img/image-20210121173620816.png)

![image-20210121173637816](http://blogs-picture.yscxy.net/img/image-20210121173637816.png)

等待片刻，macOS镜像就恢复到你的硬盘里面了（可能时间有点长）这时候我们可以做下面的工作

#### 新建启动方式

安装并打开EasyUEFI

![image-20210121173654079](http://blogs-picture.yscxy.net/img/image-20210121173654079.png)

![image-20210121173710199](http://blogs-picture.yscxy.net/img/image-20210121173710199.png)

![image-20210121173725586](http://blogs-picture.yscxy.net/img/image-20210121173725586.png)

![image-20210121173738485](http://blogs-picture.yscxy.net/img/image-20210121173738485.png)

![image-20210121173755426](http://blogs-picture.yscxy.net/img/image-20210121173755426.png)

![image-20210121175600021](http://blogs-picture.yscxy.net/img/image-20210121175600021.png)

![image-20210121173810819](http://blogs-picture.yscxy.net/img/image-20210121173810819.png)

#### 根据自己电脑的型号，关闭安全启动

如何验证是否关闭成功？

![image-20210121173830790](http://blogs-picture.yscxy.net/img/image-20210121173830790.png)

然后重启我们的电脑就会出现两个苹果图标，一个win的图标，如果想进win就左右键选win或者进mac就选中间的那个mac图标，进行一番设置激活就ok了。**不确定每台电脑都能成功，本人联想小新成功，朋友几台联想也都成功**，一般遇到的问题就是选择过后mac系统就一直有进度条走不完，这时候就去网上找一下适合自己的efi文件，替换自己的就好了！
