msi和exe的区别：
msi类似一个压缩文件，安装过程其实就是解压过程
exe是可执行文件

win + r   =>   msconfig  禁止自启动项

services.msc 打开服务

空白处 右键  分组依据 无    可以取消文件分组

winver.exe，会显示你的Windows系统版本

不要随意更改软件安装路径,这样可能会导致软件不能打开,



KB/s是KByte/s的缩写  Kb/s是Kbit/s或Kbps的缩写    KB/s通常用于传输速度，比如复制文件时。Kb/s通常用于宽带网速，比如512Kb/s宽带  虽然只是大小写不同，但表示的东西完全不一样

通常安装的宽带都是以Kb/s为单位，但实际下载的速度换算为常用的KB则完全不一样。比如：512kbps的宽带，每秒的下载速度为512/8=64KB/s。

bit：中文名称是位，音译“比特”，是用以描述电脑数据量的最小单位。
Byte：字节  是计算机信息技术用于计量存储容量的一种计量单位，也表示一些计算机编程语言中的数据类型和语言字符。
单位换算表：
	1Byte=8bit
	1KB=1024Byte(字节)=8*1024bit   KB 千字节
	1MB=1024KB                     MB 兆字节
	1GB=1024MB                     GB 吉字节
	1TB=1024GB
	1PB=1024TB
	1EB=1024PB
	1ZB=1024EB
	
bps（bits per second）是数据传输速率的常用单位，意思是比特率、比特/秒、位/秒、每秒传的位数。

比特（bit）是信息技术中的最小单位。文件大小（例如文本或图像文件）通常以字节（Byte）为单位。一字节对应八比特。在数据传输中，数据通常是串行传输的，即一个比特接一个比特地传输。数据速率的单位是比特每秒（bps），含义是每秒串行通过的位数。



Bps (Bytes per second), 即字节每秒，因为一字节对应八比特，所以1 Bps = 8bps。

比特率是指每秒传送的比特(bit)数。单位为 bps(Bit Per Second)，比特率越高，传送数据速度越快。声音中的比特率是指将模拟声音信号转换成数字声音信号后，单位时间内的二进制数据量，是间接衡量音频质量的一个指标。 

视频中的比特率（码率）原理与声音中的相同，都是指由模拟信号转换为数字信号后，单位时间内的二进制数据量。

扩展资料：

通信和计算机行业内经常利用“类似国际单位制”的前缀来表示更大的衍生单位：

1000 bit/s = 1 kbit/s （一千位每秒）

1000 kbit/s = 1 Mbit/s （一兆或一百万位每秒）
1000 Mbit/s = 1 Gbit/s (一吉比特或十亿位每秒）

（此处K和M分别为1000和1000000，而不是涉及计算机存储器容量时的1024和1048576）

大的比特率，使用国际单位制词头：

1,000 bps= 【1kbps】 =1,000 bit/s= 0.97656 Kibi bit/s

1,000,000 bps= 【1Mbps】 =1,000,000 bit/s= 0.95367 Mebi bit/s

1,000,000,000 bps= 【1Gbps】 =1,000,000,000 bit/s= 0.93132 Gibi bit/s




VPS（Virtual Private Server 虚拟专用服务器）是利用虚拟服务器软件。在一台物理服务器上创建多个相互隔离的小服务器。
这些小服务器（VPS）本身就有自己操作系统，它的运行和管理与独立服务器完全相同。

简单地说，VPN（Virtual Private Network 虚拟专用网络）在公用网络上建立专用网络，进行加密通讯。在企业网络和高校的网络中应用很广泛。
你接入VPN，其实就是接入了一个专有网络，你的网络访问都从这个出口出去，你和VPN之间的通信是否加密，取决于你连接VPN的方式或者协议。


SS全称shadowsocks  是一种基于Socks5代理方式的加密传输协议，也可以指实现这个协议的各种开发包。Shadowsocks分为服务器端和客户端，
在使用之前，需要先将服务器端程序部署到服务器上面，然后通过客户端连接并创建本地代理。

SSR全称shadowsocks-R  在Shadowsocks的基础上增加了一些数据混淆方式

vpn和ss/ssr的区别
	vpn的目的是用来加密企业数据的  vpn的流量特征很明显，以openvpn为例，流量特征明显，防火墙直接分析你的流量，如果特征匹配，直接封掉。
	对ss/ssr来说穿透防火墙是第一位，抗干扰性强，而且对流量做了混淆，所有流量在通过防火墙的时候，基本上都被识别为普通流量，
	也就是说你翻墙了，但是政府是检测不到你在翻墙的。


URI(统一资源标识符) 不一定非得是通过号码确定的。URI 是在「某一规则」下标识出一个资源的字符串，通过地址或者通过号码都是可行的规则，
其中通过地址规则实现的 URI 可以被称作 URL ，URL 是 URI 的一种实现，所以URI 作为更宽泛的定义是包含了 URL 的，
就像三角形包含等边三角形一样。

https://www.zhihu.com/question/21950864?sort=created   地址(url 统一资源定位符)     
123456789.html                                         编号(无名)		  这二者都是uri的一种实现，可以说url是uri，但不能说uri就是url


​	