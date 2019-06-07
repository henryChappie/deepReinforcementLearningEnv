# deepReinformanceLearningEnv
Use deepMind's StarCraft &amp; openai's Universe platform for resarch for Deep ReinformanceLearning by Use Ubuntu in VirtualBox

近些年来，人工智能得到了飞速的发展，特别是在机器学习领域里面的深度学习在当今时代的发展之下得到了重大的突破。作为一个开发者与技术爱好者，我同样觉得你可能会想加入到这项研究一面。

所以在这里，我写下这篇文档，这篇文章主要是为对深度强换学习环境的搭建过程做一个教程和说明，对与深度强换学习，如果您想学习，请查看资源推荐。

首先你需要下载下面的这个软件包：
Ubuntu镜像下载地址：<br>
<ul>
<li><a href='http://mirrors.163.com/'>网易镜像</a></li>
<li><a href="https://www.ubuntu.com/download/desktop">官网</a></li>
<li><a href="https://cn.ubuntu.com/">中文官网</a></li>
</ul>

虚拟机盒软件下载地址：<br>
<a href="https://www.virtualbox.org/">Oralce VirtualBox下载</a><br>
特别提醒：<br>
当然，如果您的电脑硬件条件有限或者您不想通过虚拟机的方式安装，我建议您使用<a href="https://www.docker.com/">Docker</a>进行安装，docker是一个轻量级的容器，通过docker，你也可以实现，不过由于docker的网络很不稳定，所以我选择使用虚拟机的方式来进行安装。



详细的环境搭建过程请参考上面的说明文档，您可以按照上面的说明一步一步的操作，如果您在操作的过程中遇到了问题，请可以先在网上寻找答案，如果仍然无法找到解决方案，您可以联系我，或者如果您不想亲自安装环境的话，您可以直接下载环境，我已经将环境全部部署完成并且打成了压缩包，您可以到网盘下载，不过文件有14.6G，可以会耗费很长的时间下载，这会由您的网络状况决定。
网盘下载密码：<a href='https://pan.baidu.com/s/1IL8zMFM6zjVtWfRy2Sd0dw'>bdlh</a>

注意事项:<br>
由于网盘上传文件有大小限制，所以采用了分卷压缩的方式，共4个压缩文件，请将四个压缩文件全部下载完成后全部选中一起解压以避免解压过程中可能会出现错误。

在您完成解压缩后会得到一个ova文件，这是您可以打开您的virtualbox，选择导入虚拟介质，然后选择解压后的虚拟介质文件，进行导入，这个能会花费您数个小时的时间，因为文件比较大，这由您的系统决定。

在导入后您可以选择开启虚拟机，等待几分钟后，您会看大登陆界面，点击输入登陆密码：deeprl<br>
如果这是再次回到了登陆界面，这是您可以：Ctrl+ALt+F6进入终端模式，输入：deeprl 密码：deeprl
让后执行：rm -rf .Xaulity
然后：Ctrl+Alt+F7再次进入图形化界面，再次输入密码方可进入
注意：在终端执行命令时，随后以root身份(sudo su)，以免频繁输入密码过于麻烦
代码编辑器在Download/Subline下，您可以执行通过./执行文件打开编辑器。
