# docbook是一个写作、排版、出版的利器。

* docbook官网：<http://docbook.org/>

* docbook各个版本在线文档：<http://tdg.docbook.org/>

  比如 [DocBook 5.1: The Definitive Guide](http://tdg.docbook.org/tdg/5.1/)

* docbook各个版本schema文档下载地址：<http://docbook.org/xml/>

* [DocBook 5 快速起步教程(Mac安装)](http://blog.csdn.net/sarkuya/article/details/6854323)

* 怕忘记了 :stuck_out_tongue_winking_eye: 附加一篇额外的文章讲述的是Linux系统下根目录下的主要目录的作用，[Filesystem Hierarchy Standard](http://www.pathname.com/fhs/pub/fhs-2.3.html)

* github mardown在线文档：<https://guides.github.com/features/mastering-markdown/>

* markdown支持的emoji表情：<https://www.webpagefx.com/tools/emoji-cheat-sheet/>

# 在Mac下安装docbook环境

1. 从[http://docbook.org/xml/5.0/](http://docbook.org/xml/5.0/)下载`docbook-5.0.zip`解压到`/usr/local/share/xml/docbook/docbook-5.0`。为什么是`/usr/local`下面呢是涉及到Mac的一些权限即使是root用户有些目录也没有操作权限，我也没有改。


2. 安装字符实体，从[http://www.oasis-open.org/docbook/xmlcharent/index.shtml](http://www.oasis-open.org/docbook/xmlcharent/index.shtml)下载。需要再安装这里就先跳过了

3. 安装DocBook样式表。到`sourceforge`的[DocBook项目](https://sourceforge.net/projects/docbook/files/docbook-xsl/)下载DocBook样式表，点击`docbook-xsl`的链接，可看到列出了多个版本。本文写作时最新版本为1.79.1。将其解压到`/usr/local/share/xml/docbook/docbook-xsl-1.79.1`路径下。
	![sourceforge docbook-xsl](https://github.com/dujuwen/docbook/blob/master/attachment/images/docbook-xsl.png)

4.  
