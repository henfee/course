## Fintech101 Step1 基础准备
- - - -
下面的内容是有关Fintech学习的第一步，主要涉及到一些基本知识和学习环境的准备，计划安排学习时间为2周，主要包括有

1. 操作系统相关基本知识：（必选），大约需要3小时
	* 了解操作系统，特别是linux操作系统的发展历史和常见发行版本 （30分钟）
	* linux操作系统（以ubuntu为例）的安装；（30分钟）
	* 熟悉linux操作系统的基本知识（30分钟）
	* 掌握linux操作系统的Shell（BASH为例）和常用命令行（60分钟）
	* 熟悉linux下的基本编辑器Vi的使用（30分钟）
	* 熟悉linux下安装软件包的常用命令（10分钟）
2. 版本管理的基本知识：（必选），大约需要2小时
	* 了解常见的版本管理系统（5分钟）
	* 了解git版本管理系统的基本历史（10分钟）
	* 掌握git的安装（10分钟）
	* 掌握git的初始化命令（10分钟）
	* 掌握git的常用命令（60分钟）
	* 了解github（10分钟）
	* 熟悉github的基本操作（30分钟）
3. 虚拟机软件基础（可选），大约需要1.5小时
	* 了解虚拟机技术和常用的虚拟机软件（10分钟）
	* 掌握VirtualBox的安装和配置（20分钟）
	* 掌握VirtaulBox安装虚拟操作系统的方法（30分钟）
	* 熟悉常用的Virtualbox操作（10分钟）
	* 了解VirtaulBox下网络配置方法（30分钟）
4. Docker容器技术（可选）。大约需要2小时
	* 了解Docker的基本发展历史（10分钟）
	* 了解Docker与虚拟机的区别（10分钟）
	* 掌握Docker的安装（20分钟）
	* 熟悉基本的Docker命令（60分钟）
	* 掌握如何建立自己的Docker镜像文件（30分钟）
5. Python的安装、环境设置及jupyter的安装（必选），大约需要3小时
	* Python语言的安装方法（10分钟）
	* 常见的Python语言包安装工具和常见的发行版本（10分钟）
	* 掌握Miniconda安装Python（10分钟）
	* 掌握Anaconda安装Python（10分钟）
	* 掌握pip安装Python包文件方法（10分钟）
	* 掌握conda安装Python包文件方法（10分钟）
	* 掌握virtaulenv的建立Python不同工作环境的方法（20分钟）
	* 掌握conda建立Python不同工作环境的方法（20分钟）
	* 掌握安装jupyter notebook的方法（10分钟）
	* 熟悉如何配置jupyter notebook（20分钟）
	* 熟悉如何在jupyter notebook中增加不同的（语言）内核方法（如不同的python版本，R语言、BASH、Julia等语言等）（30分钟）
	* 熟悉如何启动jupyter notebook并熟悉其基本操作（20分钟）

以上基本包括了我们开始学习Fintech所需要的基本知识和环境准备。预计整个完成所需要的时间大约为12小时。（其中虚拟机技术和Docker技术这部分是作为可选，需要3.5小时）。实际上，这个时间只是一个大概的估计，因人而异，其中还没有考虑到网络速度等因素带来的软件下载所需要的时间等，因为网络速度的原因等，实际上需要等待软件下载的时间也是差异很大的。

总的来看，这些基本准备如果分散在我们的日常时间，即便每天我们能安排2小时固定时间来学习，也是需要大概6天的时间。实际上，因为我们在搜索相关资料和学习命令的过程中，存在效率问题，而且学习还有一个学习曲线，记忆遗忘等问题等，这需要我们还需要拿出一些时间进行反复的练习，这部分准备工作可以简单理解为工具的学习，“工欲善其事，必先利其器”，花一些时间来做好这些基本准备，对于后期的学习是十分有帮助和必要的。

### **计划学习时间：2周**

---

## 准备自己的软件学习环境
```
操作系统相关基本知识：（必选），大约需要3小时
  * 了解操作系统，特别是linux操作系统的发展历史和常见发行版本 （30分钟）
  * linux操作系统（以ubuntu为例）的安装；（30分钟）
  * 熟悉linux操作系统的基本知识（30分钟）
  * 掌握linux操作系统的Shell（BASH为例）和常用命令行（60分钟）
  * 熟悉linux下的基本编辑器Vi的使用（30分钟）
  * 熟悉linux下安装软件包的常用命令（10分钟）
```

Fintech的学习在技术方面主要是偏重与python等编程语言和数据分析的学习，学习环境推荐是在linux操作系统下，不推荐使用Windows操作系统。这是因为：

1. linux下有大量的开源工具可以使用；
2. linux下有更好的版本管理工具和软件包管理
3. 基于linux能更好地与开发者交流
4. 习惯于命令行的操作，提高效率
5. ……

简而言之，我们需要准备的是一个linux操作系统环境。（如果是Apple电脑，因为其操作系统本身就是基于FreeBSD的一个版本，所以可以不用另外安装Linux操作系统。）

所以，针对于Windows操作系统，我们需要准备一个linux的操作环境，主要方法有

### * 方法1: 使用虚拟机（VirtualBox）

如果你使用的是Windows操作系统，可以通过安装虚拟机软件，比如VirtualBox， VMWare等，通过虚拟机的方式来安装一个linux操作系统，用于学习。

1. 准备VirtualBox软件
![VirtaulBox web](./pic/virtualbox.png )
	* [VirtualBox下载](https://www.virtualbox.org)
	* [VirtualBox for Windows 下载](http://download.virtualbox.org/virtualbox/5.1.26/VirtualBox-5.1.26-117224-Win.exe)
	* [VirtualBox for Mac 下载](http://download.virtualbox.org/virtualbox/5.1.26/VirtualBox-5.1.26-117224-OSX.dmg);
	* [VirtualBox for Linux 下载，选择不同的发行版本和安装方式](https://www.virtualbox.org/wiki/Linux_Downloads);
	![VirtualBox for Linux](./pic/virtualbox_linux.png)
	* [VirtualBox 5.1.26 Oracle VM VirtualBox Extension Pack下载，提供虚拟机更好的支持，比如支持USB3.0等，建议安装](http://download.virtualbox.org/virtualbox/5.1.26/Oracle_VM_VirtualBox_Extension_Pack-5.1.26-117224.vbox-extpack)

2. 准备Linux操作系统的镜像文件（推荐使用Ubuntu，推荐下载Ubuntu 16.04.3 LTS 版本的server版本，如考虑到第一次安装使用linux，可下载Desktop版本替代）

	* [Ubuntu Desktop下载，建议选择Ubuntu 16.04.3 LTS](https://www.ubuntu.com/download/desktop)
	![Ubuntu Desktop](./pic/ubuntu_desktop.png)
	* [Ubuntu Server下载，建议选择Ubuntu Server 16.04.3 LTS](https://www.ubuntu.com/download/server)
	![Ubuntu Server](./pic/ubuntu_server.png)
	* [如何安装Ubuntu Desktop？](https://tutorials.ubuntu.com/tutorial/tutorial-install-ubuntu-desktop#0)
	* [如何安装Ubuntu Server?](https://tutorials.ubuntu.com/tutorial/tutorial-install-ubuntu-server#0)
	* [Create a bootable USB stick on Windows](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-windows?_ga=2.139700662.466322648.1502078703-1860187164.1500360875#0)

	* [Create a bootable USB stick on macOS](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-macos?_ga=2.237592965.466322648.1502078703-1860187164.1500360875#0)

	* [Create a bootable USB stick on Ubuntu](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-ubuntu?_ga=2.98214554.466322648.1502078703-1860187164.1500360875#0)

	* [制作可启动U盘的工具Rufus for Windows](https://rufus.akeo.ie/downloads/rufus-2.16.exe)
	![Rufus for Windows](./pic/rufus.png)
	* [制作可启动U盘的工具 Unetbootin，支持linux、Windows、MacOS操作系统](https://unetbootin.github.io)
	![Unetbootin](./pic/unetbootin.png)

3. 安装VirtualBox软件
4. 运行VirtualBox软件，装载下载的Ubuntu镜像文件，安装Ubuntu操作系统
5. 在虚拟机上运行Ubuntu操作系统

通过虚拟机方式安装，linux操作系统作为虚拟机文件存放在Windows系统下，因为是在Windows操作系统之上通过虚拟机软件来运行另外一个操作系统，性能受到较大的限制，如果操作系统出现故障或者性能不够，影响到使用的体验，不如独立运行的linux操作系统性能强大。
另一方面，这种方式好处也很明显，使用方便，不影响原来的Windows操作系统使用，两个系统可以同时运行，不影响正常的学习工作，随时可以启动虚拟机和关闭虚拟机。

这种方式，虚拟机文件也可以保存在移动硬盘或者U盘中，使用的时候连接，但存在USB接口性能的影响。
这种方式，因为需要安装虚拟机软件，对于安装机器存在一定的依赖性，某种程度上讲，需要在某台固定的电脑上使用，方便性不足。

### * 方法2: 在移动硬盘或者U盘上安装Linux操作系统

这种方式是直接在移动硬盘或者U盘上安装Linux操作系统，启动计算机的时候，通过选择启动的顺序来选择不同的操作系统，从而实现运行linux操作系统的目的。

这种方式的好处是充分利用linux操作系统的性能优势，更能充分体会到linux环境。缺点是因为linux发行版本等问题，对于许多笔记本硬件的驱动支持不够，可能会造成驱动安装不完整等问题，无法充分发挥硬件的性能；同时，因为其启动是独立的linux系统，如果要使用Windows系统，需要退出当前进行的工作，重新启动计算机进入Windows系统，在两个系统中进行切换，这会带来很多操作上的不便。

这种方法的基本操作：
1. 下载linux操作系统的镜像文件
2. 下载和安装Windows版本的Boot image制作工具
3. 通过制作的Linux的boot启动盘，重新启动计算机，进入linux启动引导盘
4. 通过linux启动引导盘，在本机硬盘空闲分区（不推荐）或者移动硬盘、U盘上安装linux操作系统
5. 从安装的移动硬盘或者U盘上重新启动linux

如果采用此方法，推荐在移动硬盘上进行安装，或者准备一个容量较大（大于64G）的U盘，在U盘上安装，作为本次学习的学习环境。
这种方法的好处是，操作系统在移动硬盘或者U盘上，可以很方便的随身携带，意味着你可以随时方便地利用你周围环境的计算机（台式机、笔记本等），接入你的移动硬盘或者U盘，重新启动，就可以开始学习（可能需要根据具体机器进行基本的显示分辨率、网络设置等基本设置就可以正常使用）。

### * 方法3: 使用Docker容器

这种方式类似于第一种方式，Docker容器技术是虚拟化技术发展的一个方向和趋势，有助于提高虚拟化的效率。
有关Docker的知识，可以参阅网站？？

Docker可以在多种操作系统下使用，包括Windows操作系统和Apple公司的操作系统。

这种方法的基本操作是：

1. 下载安装Docker软件

	* [ 下载docker for MAC ](https://www.docker.com/docker-mac)；

	* [ 下载Docker for Windows ](https://www.docker.com/docker-windows)；

	* [ 下载Docker for Ubuntu ](https://www.docker.com/docker-ubuntu)

	* [ 如何安装docker? ](https://docs.docker.com/engine/installation/)；

2. 运行Docker
	* [Docker 帮助文档 ](https://docs.docker.com/get-started/)
	* [Docker 中文教程 ](http://www.runoob.com/docker/docker-tutorial.html)
	* [Docker —— 从入门到实践](http://wiki.jikexueyuan.com/project/docker-technology-and-combat/),[PDF下载](http://wiki.jikexueyuan.com/download/docker-technology-and-combat/pdf/)
	* [极客学院 Docker中文教程 ](http://wiki.jikexueyuan.com/project/docker/),[PDF下载](http://wiki.jikexueyuan.com/download/docker/pdf/)

3. 下载所需要的Docker镜像文件（如Ubuntu镜像）
	* 可用docker命令行下载Ubuntu的镜像文件： docker pull ubuntu

4. 运行下载的镜像文件

这种方式下，由于使用docker技术，虚拟化的效率更加高效；但因为docker技术的应用目标，对于镜像文件，主要是一个镜像集中在一个功能上，这使得其使用上与一个独立的操作系统还是存在一些差异，特别是在对镜像文件的图形化界面操作等；
这种方式，因为效率较高，对于机器的系统资源占用不如虚拟机软件那么高，对于作为linux学习和某一功能的使用（比如启动jupyter notebook）具有可取之处，也作为一种方法推荐。

这种方式，因为需要先安装docker软件，也同方法1一样，受到安装机器限制，存在依赖性，某种程度上讲，需要在某台固定的电脑上使用，方便性不足。

---

## Linux 基础

```
操作系统相关基本知识：（必选），大约需要3小时
  * 了解操作系统，特别是linux操作系统的发展历史和常见发行版本 （30分钟）
  * linux操作系统（以ubuntu为例）的安装；（30分钟）
  * 熟悉linux操作系统的基本知识（30分钟）
  * 掌握linux操作系统的Shell（BASH为例）和常用命令行（60分钟）
  * 熟悉linux下的基本编辑器Vi的使用（30分钟）
  * 熟悉linux下安装软件包的常用命令（10分钟）

```
![linux](./pic/linux_history.png)


关于linux的学习资料，网络上非常多，各种linux发行版本也提供了非常详尽的使用帮助。最好的学习就是，安装一个linux系统（比如通过虚拟机安装linux，可以快速开始学习，同时来简化安装中可能遇到的的各种硬件兼容性问题），在Linux中去动手操作，不断熟悉和熟练。这是一个不断反复的过程，也是一个习惯养成的过程，根据每个人的学习习惯等需要的时间也不同，但一般来说，掌握基本的用法和常用的命令，启动和管理一些基本的服务和应用（比如web服务等），不是一件很难的事情，这也是后续学习python编程和数据分析等的基础，需要认真掌握。


下面提供的一些网上学习资源，主要用于快速入门，方便学习。

* [一步一步学 Linux](http://wiki.jikexueyuan.com/project/learn-linux-step-by-step/),[PDF文档下载](http://wiki.jikexueyuan.com/download/learn-linux-step-by-step/pdf)

* [Linux 入门教程](http://wiki.jikexueyuan.com/project/linux/),[PDF下载](http://wiki.jikexueyuan.com/download/linux/pdf/)

* [Linux 工具](http://wiki.jikexueyuan.com/project/linux-tools/),[PDF下载](http://wiki.jikexueyuan.com/download/linux-tools/pdf/)

* [Linux 命令行](http://wiki.jikexueyuan.com/project/linux-command/),[PDF下载](http://wiki.jikexueyuan.com/download/linux-command/pdf/)

* [两个月精通 Shell 脚本](http://wiki.jikexueyuan.com/project/learn-shell/),[PDF下载](http://wiki.jikexueyuan.com/download/learn-shell/pdf/)

* [Vim在线练习](http://www.openvim.com/tutorial.html)





---

## git基础，管理你的代码

```
版本管理的基本知识：（必选），大约需要2小时
  * 了解常见的版本管理系统（5分钟）
  * 了解git版本管理系统的基本历史（10分钟）
  * 掌握git的安装（10分钟）
  * 掌握git的初始化命令（10分钟）
  * 掌握git的常用命令（60分钟）
  * 了解github（10分钟）
  * 熟悉github的基本操作（30分钟）
```

git是目前最流行和重要的版本管理工具，对于编程学习来言，对于代码、文档、项目的管理是基础，也是最基本的要求，这需要在开始编程学习之前就了解掌握这个工具，并能熟练地应用。通过github，你可以免费得到大量的优秀开发项目的代码，通过阅读他人的代码，这是一种非常有效的学习提高的方式。

git的学习资料很多，我列出了一些网上的资料，供大家学习。其中githug通过游戏通关方式来测试你对git的掌握，可以用来建议你对于git的熟悉情况，建议试一试。

1. 安装Git
	* [git官方网站](https://git-scm.com)
	* [git官方在线教程](https://try.github.io/levels/1/challenges/1)
	* [git 教程](http://www.runoob.com/git/git-tutorial.html)
	* [git 简明教程](http://www.runoob.com/manual/git-guide/)
	* [git 5分钟教程](http://www.runoob.com/w3cnote/git-five-minutes-tutorial.html)
	* [git教程 by 廖雪峰](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
	* [git 在线练习](http://learngitbranching.js.org)
	* [沉浸式学 Git](http://wiki.jikexueyuan.com/project/git-immersion/)，[下载PDF文档](http://wiki.jikexueyuan.com/download/git-immersion/pdf/)
	* [通过游戏来学习，Githug 通关攻略](http://wiki.jikexueyuan.com/project/githug-walkthrough/)
	* [闯过这 54 关，点亮你的 Git 技能树](http://wiki.jikexueyuan.com/project/git-54-stage-clear/),[PDF下载](http://wiki.jikexueyuan.com/download/git-54-stage-clear/pdf/)
	* [git 详解](http://www.open-open.com/lib/view/open1328069609436.html)
	* [常用 Git 命令清单 by 阮一峰](http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html?utm_source=tool.lu)

2. github使用
	* [Github官网](https://github.com)
	* [github 简明教程](http://www.runoob.com/w3cnote/git-guide.html)

---
## Python 的安装和配置

```
Python的安装、环境设置及jupyter的安装（必选），大约需要3小时
	* Python语言的安装方法（10分钟）
	* 常见的Python语言包安装工具和常见的发行版本（10分钟）
	* 掌握Miniconda安装Python（10分钟）
	* 掌握Anaconda安装Python（10分钟）
	* 掌握pip安装Python包文件方法（10分钟）
	* 掌握conda安装Python包文件方法（10分钟）
	* 掌握virtaulenv的建立Python不同工作环境的方法（20分钟）
	* 掌握conda建立Python不同工作环境的方法（20分钟）
	* 掌握安装jupyter notebook的方法（10分钟）
	* 熟悉如何配置jupyter notebook（20分钟）
	* 熟悉如何在jupyter notebook中增加不同的（语言）内核方法（如不同的python版本，R语言、BASH、Julia等语言等）（30分钟）
	* 熟悉如何启动jupyter notebook并熟悉其基本操作（20分钟）

```

Python是一种解释型、面向对象、动态数据类型的高级程序设计语言。
Python由Guido van Rossum于1989年底发明，第一个公开发行版发行于1991年。Python 源代码遵循 GPL(GNU General Public License)协议。

Python是目前非常热门并在数据分析中应用普遍的一种编程语言，也是普遍认为入门较为容易的一门语言，在金融科技的学习中，我们推荐学习Python。


### Python下载

![Python website](./pic/python.png)

Python最新源码，二进制文档，新闻资讯等可以在Python的官网查看到：
[Python官网](http://www.python.org/)
你可以在以下链接中下载 Python 的文档，你可以下载 HTML、PDF 和 PostScript 等格式的文档。
[Python文档下载地址](http://www.python.org/doc/)

### Python的安装

Python已经被移植在许多平台上（经过改动使它能够工作在不同平台上），根据不同操作系统，可以直接到python的官方网站上去下载源代码或者安装文件自行安装。一般linux的发行版本都集成了python，Apple电脑所用的macOS系统也一般预装了python，所以不用另行安装；主要是Windows操作系统下，需要下载python的安装文件进行安装。


```
* Unix & Linux 平台安装 Python:
    * 打开WEB浏览器访问http://www.python.org/download/
    * 选择适用于Unix/Linux的源码压缩包。
    * 下载及解压压缩包。
    * 如果你需要自定义一些选项修改Modules/Setup
    * 执行 ./configure 脚本
    * make
    * make install
    执行以上操作后，Python会安装在 /usr/local/bin 目录中，Python库安装在/usr/local/lib/pythonXX，XX为你使用的Python的版本号。
```

```
* Window 平台安装 Python:

    * 打开WEB浏览器访问http://www.python.org/download/
    * 在下载列表中选择Window平台安装包，包格式为：python-XYZ.msi 文件 ， XYZ 为你要安装的版本号。
    * 要使用安装程序 python-XYZ.msi, Windows系统必须支持Microsoft Installer 2.0搭配使用。只要保存安装文件到本地计算机，然后运行它，看看你的机器支持MSI。Windows XP和更高版本已经有MSI，很多老机器也可以安装MSI。
    * 下载后，双击下载包，进入Python安装向导，安装非常简单，你只需要使用默认的设置一直点击"下一步"直到安装完成即可。

```

```
* MAC 平台安装 Python:

最近的Macs系统都自带有Python环境，你也可以在链接 http://www.python.org/download/ 上下载最新版安装。

```

Python的学习参考资料：

* [python官方网站](https://www.python.org)，可以下载最新的python软件，浏览学习文档；
* [Python官网下载Windows操作系统下的安装文件](https://www.python.org/downloads/windows/)，包含多种版本和安装文件形式。
* [Beginner's Guide to Python 中文](https://wiki.python.org/moin/BeginnersGuideChinese),官网的python学习指南，提供了一些学习python的参考资源。

### python第三方模块（包管理）及Python的发行版本

Python语言除了内建的模块外，还有大量的第三方模块（包），这些模块通常采用包的方式进行管理。基本上，所有的第三方模块（包）都会在[PyPI - the Python Package Index](https://pypi.python.org/)上注册，通过模块名字，可以使用pip等包管理工具进行安装。

常见的python的包管理工具有：

* disutils、setuptools、distribute，可以用于打包和安装包。
* easy_install、pip，不能打包，主要用于安装包，它在disutils的基础上增加了自动识别包依赖。

目前常用的包管理工具是pip。

* pip包管理工具：
pip可以运行在Unix/Linux, OS X, and Windows平台上，pip是python的包安装工具，其安装非常方便。
下载pip的安装包[get-pip.py](https://bootstrap.pypa.io/get-pip.py)，运行命令`python get-pip.py`就可以安装pip了。当然，也有别的方法进行安装，你可以通过搜索找到这些方法。

* conda包管理工具：
conda也是另外一种常用的python包管理工具。
conda，除了是一个包管理工具，也是一个环境管理工具，可以适用于多种语言，如python，R，Java等（Conda is a Package, dependency and environment management for any language: Python, R, Scala, Java, Javascript, C/ C++, FORTRAN）
conda安装和管理python包非常方便，可以在指定的python环境中安装包，且自动安装所需要的依赖包，避免了很多拓展包冲突兼容问题。大部分包都可以使用conda安装，无法使用conda和anaconda.org安装的包可以通过pip命令安装。



### 常见的Python科学计算发行版本
Python存在很多的发行版本，每个人根据自己的习惯，选择不同版本的Python和不同的第三方模块（包），制作自己的Python版本。
随着Python在科学计算、数据分析等领域的普及应用，出现了一些主要面向科学计算的Python发行版本，主要有：

* [Python（x，y）](https://python-xy.github.io/)

曾经是Windows系统下科学免费Python发行版的不二选择，GUI基于PyQt，曾经是功能最全也是最强大的，目前主要被WinPython替代。
![Python(x,y)](./pic/python_xy1.png)


* [WinPython](https://winpython.github.io)

适合Windows下的发行版本，WinPython功能也是比较全的,软件包比较新，GUI基于PyQt，不过相对于Python（x，y），它主要是关注便携式安装体验：你可以把它装在u盘里面。
![Winpython](./pic/winpython.png)


* [Anaconda](https://www.continuum.io/anaconda-overview)

Anaconda的开发和维护中有Python创始人和社区的核心成员，适用多种操作系统，无论是linux，还是Windows，又或是Mac，**强烈推荐Anaconda！**
包管理使用conda，GUI基于PySide，所有的包基本上都是最新版，没有PyQt和wxpython等，容量适中，但该有的科学计算包都有：numpy，sicpy，matplotlib，spyder.....
![anaconda](./pic/anaconda.png)



* [Enthought Canopy](https://www.enthought.com)

Enthought Canopy中集成了Pyhton包的在线升级和管理系统，很是方便。由于是商业级别的，Canopy的性能和稳定性超强!Enthought提供免费的free版本和学术版本（用于教育科研也是免费的）, GUI基于wxpython,包含PySide,但不包括PyQt. WxPython使用起来是比较方便，但是远没有PyQt和PySide流行，需要使用PyQt的可以自己安装。Canopy有自己的集成开发环境（IDE），里面的代码智能提示和自动补全功能不比IPython差的！如果你有学校邮箱的话，可以在Enthought的网站注册一下，选择学术+full的发行版本，会让你的工作如虎添翼的。

![enthought](./pic/enthought.png)


### 安装Anaconda
Anaconda是Python的一个开源发行版本，主要面向科学计算。我们可以简单理解为，Anaconda是一个预装了很多我们用的到或用不到的第三方库的Python。而且相比于大家熟悉的pip install命令，Anaconda中增加了conda install命令。当你熟悉了Anaconda以后会发现，conda install会比pip install更方便一些。

Anaconda是一个用于科学计算的Python发行版，支持 Linux, Mac, Windows系统，提供了包管理与环境管理的功能，可以很方便地解决多版本python并存、切换以及各种第三方包安装问题。Anaconda利用工具/命令conda来进行package和environment的管理，并且已经包含了Python和相关的配套工具。

**conda和Anaconda/Miniconda的区别**


* conda可以理解为一个工具，也是一个可执行命令，其核心功能是包管理与环境管理。包管理与pip的使用类似，环境管理则允许用户方便地安装不同版本的python并可以快速切换。conda将几乎所有的工具、第三方包都当做package对待，甚至包括python和conda自身！因此，conda打破了包管理与环境管理的约束，能非常方便地安装各种版本python、各种package并方便地切换。

* Anaconda是一个打包的集合，里面预装好了conda、某个版本的python、众多packages、科学计算工具等等，所以也称为Python的一种发行版。

* Miniconda，它只包含最基本的内容——python与conda，以及相关的必须依赖项，对于空间要求严格的用户，Miniconda是一种选择。



> To download conda, you will download Anaconda or Miniconda
>
> * Should I download Anaconda or Miniconda?
> * Choose Anaconda if you:

> Are new to conda or Python
> Like the convenience of having Python and over 150 scientific packages automatically installed at once
Have the time and disk space (a few minutes and 3 GB), and/or
Don’t want to install each of the packages you want to use individually.
> Anaconda download: http://continuum.io/downloads
>
> * Choose Miniconda if you:
>
> Do not mind installing each of the packages you want to use individually
Do not have time or disk space to install over 150 packages at once, and/or
Just want fast access to Python and the conda commands, and wish to sort out the other programs later.
Miniconda download: https://conda.io/miniconda.html
>


**Anaconda的安装**

Anaconda的安装可以直接到[官网下载]((https://www.continuum.io/anaconda-overview))，Linux、Mac、Windows均支持。

![anaconda](./pic/anaconda3.png)

安装时，会发现有两个不同版本的Anaconda，分别对应Python 2.7和Python 3.6，两个版本其实除了这点区别外其他都一样。后面我们会看到，安装哪个版本并不本质，因为通过环境管理，我们可以很方便地切换运行时的Python版本。

下载后直接按照说明安装即可。
tips：尽量按照Anaconda默认的行为安装——不使用root权限，仅为个人安装，安装目录设置在个人主目录下（Windows就无所谓了）。这样的好处是，同一台机器上的不同用户完全可以安装、配置自己的Anaconda，不会互相影响。


**设置国内镜像**

因为Anaconda.org的服务器在国外,有时候你会发现conda下载的速度经常很慢。这时候，你可以修改conda的配置，加入国内的源，比如清华TUNA镜像源有Anaconda仓库的镜像，这样可以提高conda更新和下载包的速度。具体方法如下：

```
# 添加Anaconda的TUNA镜像
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/


# 设置搜索时显示通道地址
conda config --set show_channel_urls yes

```

cheat-sheet 下载：
[Conda cheat sheet](http://conda.pydata.org/docs/_downloads/conda-cheatsheet.pdf)

**设置多个版本的Python环境**

Python语言有2.x和3.x等不同的版本，很多时候我们在学习、应用、测试中需要使用不同版本的Python，甚至我们每个项目可能都需要不同的python版本和环境，这就涉及到安装配置多版本python环境的问题。

* [Virtualenv](http://virtualenv.readthedocs.io)

  Virtualenv是一个用来创建独立的Python环境的包，为应用提供了隔离的Python运行环境，解决了不同应用间多版本的冲突问题。
  * [virtualenv官方指南](http://virtualenv.readthedocs.io/en/stable/)，最权威详尽的关于virtualenv的使用说明，包含了其他一些扩展的学习资料。（[PDF下载]([virtualenv](http://virtualenv.readthedocs.io) )）

  如果没有更多的时间来学习，可以通过下面的教程快速了解和掌握最常用的命令，满足基本使用要求。

    * [廖雪峰的virtualenv教程](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001432712108300322c61f256c74803b43bfd65c6f8d0d0000)
    * [简书上的virtualenv教程](http://www.jianshu.com/p/08c657bd34f1)


* [Conda](https://conda.io/docs/using/envs.html#create-an-environment)

	Conda不仅是一个python的包管理工具，同时，也是一个python的环境管理器，可以方便地满足多版本多环境的设置问题。如果我们使用Anaconda或者miniconda发行版本进行python安装，则可以直接使用conda来进行python多环境的设置。

  * [Conda 环境设置的方法](https://conda.io/docs/using/envs.html#create-an-environment)，这是Conda官方的帮助文档，介绍详尽。
	  网络上也有很多简要的conda环境设置的教程和参考资料，可供快速掌握。
    * [简书上的conda环境设置简明教程1](http://www.jianshu.com/p/aef6ff9730df)
	* [简书上的conda环境设置简明教程2](http://www.jianshu.com/p/d2e15200ee9b)

---

## Jupyter notebook

[Jupyter notebook](http://jupyter.org)（此前被称为 IPython notebook）是一个交互式笔记本，可支持运行python、R等多种编程语言，其本质是一个 Web 应用程序，便于创建和共享交互式计算的程序文档，支持实时代码，数学方程，可视化和 markdown，广泛用于数据清理和转换，数值模拟，统计建模，机器学习等等应用领域。

> The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, machine learning and much more.
>


Jupyter notebook是从IPython项目演变而来的，专注于使用Python进行交互式计算来应对科学计算的需求和工作流程。2011年，由 Brian Granger 领导的 IPython 团队开始开发一种基于Web技术的交互式计算文档格式，即 IPython Notebook。为什么说它是文档格式，而非计算工具呢？实际上它两者都是。Notebook 在交互上使用了 C/S 结构，它通过 Tornado 建立一个 shell 服务器，并使用浏览器作为客户端。另外 notebook 页面都被保存为 .ipynb 的类 JSON 文件格式。这种文件格式也是 Notebook 最吸引人的地方。

随着IPython Notebook被SciPy社区迅速采用，大家很快就很清楚地发现它的底层架构可以用于任何交互式的编程语言。随后在很短的时间内，除Python之外的其他语言（Julia、Haskell、R等）的内核就被连续地创建了出来。在2014年，Ipython notebook重命名为Jupyter。这个名字的灵感来自Julia、Python和R（数据科学的三种开源语言），但这个名字代表了超越了任何特定语言的通用思想：即计算、数据和人类的理解、共享和协作的活动。




关于Jupyter Notebook的介绍，简书上这篇文章[Jupyter notebook](http://www.jianshu.com/p/fed4e5dde2da)给予了很简单清晰的介绍，包括了jupyter的安装和启动等，可供快速了解学习。

Jupyter notebook 源自 Fernando Perez 发起的 IPython 项目。IPython 是一种交互式 shell，与普通的 Python shell 相似，但具有一些很好的功能（例如语法高亮显示和代码补全）。最初，notebook 的工作方式是，将来自 Web 应用（你在浏览器中看到的 notebook）的消息发送给 IPython 内核（在后台运行的 IPython 应用程序）。内核执行代码，然后将代码发送回 notebook。

核心点是 notebook 的服务器。你通过浏览器连接到该服务器，而 notebook 呈现为 Web 应用。你在 Web 应用中编写的代码通过该服务器发送给内核。内核运行代码并将代码发送回该服务器，之后，任何输出都会返回到浏览器中。保存 notebook 时，它作为 JSON 文件（文件扩展名为 .ipynb)写入到该服务器中。

此架构的一个优点是，内核无需运行 Python。由于 notebook 和内核分开，因此可以在两者之间发送任何语言的代码。例如，早期的两个非 Python 内核分别用于 R 语言和 Julia 语言。使用 R 内核时，用 R 编写的代码将发送给执行该代码的 R 内核，这与在 Python 内核上运行 Python 代码完全一样。IPython notebook 已被改名，因为 notebook 变得与编程语言无关。新的名称 Jupyter 由 Julia、Python 和 R 组合而成。如果有兴趣，不妨看看可用内核的列表。

另一个优点是，可以在任何地方运行服务器，并且可通过互联网访问服务器。通常，你会在存储所有数据和 notebook 文件的自有计算机上运行服务器。但是，你也可以在远程计算机或云实例（如 Amazon 的 EC2）上设置服务器。之后，可以在全球任何地方通过浏览器访问 notebook。

（以上文字摘自链接：[http://www.jianshu.com/p/fed4e5dde2da](http://www.jianshu.com/p/fed4e5dde2da)）

另外还有一篇文章推荐，[左手程序员，右手作家：你必须会的Jupyter Notebook](http://www.jianshu.com/p/86117613b7a6)，这篇文章也是对于jupyter notebook的一个快速介绍，帮助你快速学习使用。







**强烈推荐使用jupyter notebook来进行日常python学习和后续的有关数据抓取、数据分析、数据展现等学习。**








---

### Python参考学习资料
下面整理了一些来自网络上的python中文学习资料，方便参考学习。大家根据自己的学习习惯和学习进度选择其中一部分来作为入门学习的资料就可，这些资料主要是介绍的python语言的知识，更多的应用和练习，大家可以搜索网络，比如一些python的论坛、专题网站等，找到更多的应用案例，通过别人的应用来快速了解python在工作生活中的具体应用，从而提高自身对python 的理解和应用能力。“在实践中去学习”。

python 初级学习：

* [Python2 基础教程](http://www.runoob.com/python/python-tutorial.html)
* [Python 3 教程](http://www.runoob.com/python3/python3-tutorial.html)
* [廖雪峰的python3教程](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)
* [廖雪峰的python实战练习： 搭建一个blog网站](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001432170876125c96f6cc10717484baea0c6da9bee2be4000)
* [《零基础学 Python》(第二版)](http://wiki.jikexueyuan.com/project/start-learning-python/),[PDF下载](http://wiki.jikexueyuan.com/download/start-learning-python/pdf/)
* [简明 Python 教程](http://wiki.jikexueyuan.com/project/simple-python-course/) ，[PDF下载](http://wiki.jikexueyuan.com/download/simple-python-course/pdf/)
* [笨办法学 Python](http://wiki.jikexueyuan.com/project/learn-python-hard-way/),[PDF下载](http://wiki.jikexueyuan.com/download/learn-python-hard-way/pdf/)
* [Python 入门指南](http://wiki.jikexueyuan.com/project/python-tutorial/),[PDF下载]()
* [Python 学习笔记](http://wiki.jikexueyuan.com/project/the-python-study-notes-second-edition/),[PDF下载](http://wiki.jikexueyuan.com/download/the-python-study-notes-second-edition/pdf/)

* [Python 之旅](http://wiki.jikexueyuan.com/project/explore-python/),[epub格式下载](https://github.com/ethan-funny/explore-python/files/691859/explore-python.epub.zip)

python 中级学习：

* [Python 实战-从菜鸟到大牛的进阶之路](http://wiki.jikexueyuan.com/project/python-actual-combat/),[PDF下载](http://wiki.jikexueyuan.com/download/python-actual-combat/pdf/)
* [Python进阶](http://wiki.jikexueyuan.com/project/interpy-zh/),[PDF下载](https://github.com/eastlakeside/interpy-zh/releases/download/v1.3-StableEdition/interpy-zh-v1.3.pdf)

有关python网络爬虫相关学习资料：

* [Python 爬虫学习系列教程](http://wiki.jikexueyuan.com/project/python-crawler-guide/),  [PDF下载]()
* [Python 网络爬虫](http://wiki.jikexueyuan.com/project/python-crawler/),  [PDF下载]()
* [Scrapy 中文指南](http://wiki.jikexueyuan.com/project/scrapy/),Scrapy 是一个为了爬取网站数据，提取结构性数据而编写的应用框架。[PDF下载](http://wiki.jikexueyuan.com/download/scrapy/pdf/)


---

---
作者: 曹旭斌

时间: 2017-08-08

版本: 0.0.1a
