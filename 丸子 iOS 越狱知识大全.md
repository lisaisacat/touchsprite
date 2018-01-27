# 丸子 iOS 越狱知识大全

标签（空格分隔）： 脚本开发

---
##目录
[TOC]


##写在前面
> 2015 年 4 月之前，我还没见过到底什么是越狱。虽然做了几年游戏策划，听说过越狱手机可以破解内购却从来不知道越狱到底是怎么一回事，觉得一定是很麻烦的黑科技。
然而到了触动工作以后，发现越狱其实没有那么难，尤其是 iOS8 以后，越狱工具也在尽量做得越来越简单，只不过是有些坑刚开始遇到的时候比较头疼。
在百度和威锋论坛的帮助下，偶尔也会翻墙去看看，在几个月以后，越狱就变成一件很简单的事情了。
在积累的过程中，我把自己的一些学习心得记录下来，希望不管你是工作室还是开发者，或者纯粹的小白用户，关于越狱的问题都能在这里找到答案。

##视频教程
####Cydia 越狱步骤和必备插件
> 工作室和开发者必看！如何越狱才能避免出现问题？
链接: https://pan.baidu.com/s/1slLqBhz 密码: he2w


##越狱常识
###手机能不能越狱
> 很多小白都不大明白什么样的手机才可以越狱/root做脚本开发，下面就来说一说。
首先呢，来说说苹果 iOS 系统，能不能越狱和你用的是iPhone 还是 iPad 一丁点儿关系都没有，只和你的设备系统版本有关。
截止到目前为止 iOS6/7/8.0-8.4/9.0-9.3.3/10.0-10.3.3 都是可以越狱的（10.2 之后的越狱只支持 32 位系统也就是 iPhone5/5C）。
需要注意的是，iOS 7 系统的手机越狱失败几率很高，如果遇到越狱失败，你的手机又是 4S的话，可以考虑重刷系统再越狱，虽然也不能保证就能成功了O(∩_∩)O哈哈~
虽然都可以越狱，但是由于iOS 7 比较古老，有好些游戏已经不支持了；iOS 9 改了系统字体，还有很多系统权限都变了导致点击啊取色啊这些也和 iOS 8不一样了，所以，要做脚本开发的话最好就是用 iOS 8的设备咯~
当然如果你做的是玩家脚本开发，那就是最好 iOS8/9 都要有一部。
或者你可以访问这个网站看一看：https://canijailbreak.com/

###是否能完美越狱
|系统版本|能否越狱|是否完美越狱|推荐越狱工具|注意事项|
|--|--|--|--|--|
|iOS6|能|是|爱思助手|触动 iOS v3.0 已不支持 iOS6|
|iOS7.0 - 7.1.2|能|是|PP助手|容易出现各种奇怪的问题|
|iOS8.0 - 8.4|能|是|PP助手|主流完美越狱|
|iOS8.4.1|能|是|[EtasonJB][1]|支持 5/5C|
|iOS9.0 - 9.1|能|是|PP助手|支持 5S 以后的设备|
|iOS9.2 - 9.3.3|能|否|PP助手|支持 5S 以后的设备|
|iOS9.1 - 9.3.4|能|否|[Home Depot][2]/[Jailbreak.me][3]|支持 5/5C|
|iOS9.3.5|能|否|[Phœnix][4]|支持 5/5C|
|iOS10.0.1 - 10.2|能|否|PP助手|支持 5S 以后的设备|
|iOS10.2.1|能|否|[Saigon][5]|支持 6/6P|
|iOS10.0 - 10.3.3|能|否|[H3lix][6]|支持 5/5C|
|iOS10.3 - 10.3.3|能|否|[G0blin][7]|支持 5S 以后的设备|


**注意事项：**
>非完美越狱，意味着每次重启手机后都需要重新激活越狱。


###购买渠道
> 万能的淘宝！
做脚本开发的话，买一部二手设备足矣。
一搜索，你就会发现价格真是差很多啊~所谓的美版日版国行港行、有锁和无锁是虾米意思？
美版，顾名思义，就是在美国卖的手机啦~
不同国家卖的手机会有一些区别，比如只能插入特定的手机卡。
有锁就是说你只能使用指定运营商的手机卡，别的运营商是不能激活的哦~所以！有锁的越狱设备轻易不要刷机升级系统，否则会变砖！
但是因为是买回来做脚本开发的并不是要用来打电话，有锁的美版日版会更便宜，理所当然就成为最佳选择了。

**注意事项**

> 1. 如果你的手机是有锁的，越狱后千万千万不要刷机和升级系统版本，因为你会发现不管你是塞移动联通电信还是什么卡进去都不能激活设备了。
2. 如果你真的不幸把设备给刷机了，那么还有一点点希望，用手机序列号等信息确定到底是要用哪个运营商的手机卡才能激活。然后再去万能的淘宝买一张激活卡，大概十几块钱，但是由于确定运营商本身就是一件比较困难的事情，so~最好是在你买到有锁设备的时候就打开设置看一眼运营商是啥然后做一下记录吧！
3. 越狱的设备千万不能在设置里点击那个**抹掉所有内容和设置**，会变砖！

###各国及地区运营商
> 买到一部有锁的机器，首先要做好信息备份，看一看自己的手机是哪一国哪个运营商的，万一白苹果了还能知道买啥激活卡。
在淘宝上能买到的机器以美版和日版为主，也会有少量的英版，其他版本的目前还没见过。

|国家/地区|运营商|
|--|--|
|加拿大|Bell/Fido/Rogers/Telus|
|美国|AT&T/Sprint/Verizon/T-Mobile|
|德国|T-Mobile/Vodafone|
|英国|3/O2/Orange/T-Mobile/Vodafone|
|法国|Bouygues/Orange/SFR|
|澳大利亚|Optus/Telstra/Vodafone|
|日本|au/SoftBank/docomo|
|韩国|olleh|
|菲律宾|Globe|
|西班牙|Movistar/Orange/Vodafone|

###有锁 iPhone 激活
> 一旦出现白苹果，或者进入 DFU 模式无法退出的情况，那么就只剩下刷机了。
刷机之后无法越狱先不提，机子有锁的话无法激活就真的变砖头了。
所以拿到新设备一定在关于本机中查看运营商信息并做好记录，在这里推荐一个在线文档：[一起写][8]，完全免费的。

###安全模式
<center>![image.png-163.1kB][9]</center>
当手机顶部出现一行字：Exit Safe Mode,就代表手机进入了安全模式，屏幕上会弹出一个提示框提示重启手机退出安全模式，点击 Restart 即可。

**出现原因**
至于进入安全模式的原因，无非就是装了和系统不兼容的插件，这种情况经常发生在刚刚推出一个新的越狱系统插件还没做适配的阶段。
或者 Cydia 变更界面有太多的基础插件没有升级，这种情况经常发生在新越狱手机，Cydia 版本太旧没有升级的时候。

**解决办法**
就是卸载掉不兼容插件或者升级 Cydia.


##iOS 手机常用操作
###强制关机
> 越狱手机偶尔遇到手机卡死任何操作都没反应的情况，iOS 10 越狱系统更是经常发生，这个时候就只能强制重启手机。
一种方法是把手机连上电脑，用 PP 助手或者其他工具的重启功能。
同时按下 Home 键和电源键，长按 15 秒以上，直至屏幕变黑再松手。
![image.png-119.2kB][10]

###不加载插件进入系统
> 有时候安装完新插件或者更新后，会出现白苹果、蓝屏、无限重启、底部 Dock 栏消失等各种问题，一般都是由于插件版本与系统不兼容导致的，只要卸载或降级插件即可。
但是根本进不去系统，怎么办呢？
同时按住开机键和音量加+，就相当于电脑的安全模式，不加载任何插件开机，就可以进行操作了。

###进入 DFU 模式
> 有时候手机出现白苹果或者黑苹果，手机重启无法正常进入系统了，这个时候需要进入 DFU 模式看看手机是否还有救。
同时按下 Home 键和电源键，长按 30 秒以上，直到手机屏幕出现白苹果，松开电源键，直到屏幕上出现一根线连着粉红色的 iTunes 标志。
或者连接电脑，用爱思助手进入 DFU 模式，但是经常失败，还是建议手动操作。

##越狱装机流程
###1. 越狱工具的选择
> iOS 7 和 8 系统越狱推荐使用**爱思助手**，不管是老版本系统还是最新的越狱系统都能找到越狱工具，不用再挨个去下载了。
唯一值得诟病的就是每次爱思都会强制安装自己的 App 到手机。
iOS9 和 10 系统推荐使用 **PP 助手**越狱，因为非完美越狱系统使用爱思越狱会导致触动出现莫名其妙的 bug,大概还是越狱环境有问题吧。
<center>![image.png-47.9kB][11]</center>


###2. 删除无用源
> 把除了Bisboss 源还有Cydia 作者那个源之外的无用源删掉，一是没啥用占地方，二就是这些源都在国外，动不动就连不上了报错影响后面安装其他插件。

###3. 升级插件
> 越狱完成后，首先要刷新软件源，把该升级的插件全部升级。

**注意事项：**
> 最近遇到几个工作室用户的 **iOS7.1.2** 系统在升级插件之后重启手机无限白苹果蓝屏，这是由于依赖插件 Cydia Subatrae 最新版与 iOS7 不兼容导致的（毕竟是好几年前出的越狱了）。
同时按住开机键和音量键大概十几秒左右，直到手机振动，松开，这时候就可以不加载插件进入系统了。
打开 Cydia，将 Cydia Substrate 插件降级到可以降到的最低版本，就可以解决这个问题了。
所以如果你的设备也是 7 系统，在升级插件之前，需要关掉 Cydia Substrate 插件的升级，方法如下：
已安装 -> Cydia Substrate -> 更改软件包设置 - 打开忽略更新开关
<center>![忽略更新.png-99.8kB][12]</center>

###4. 安装必备插件
> 非常重要！！！
因为有太多用户拿到越狱手机之后没有安装这些插件，当手机遇到 Cydia 闪退、空白、无法安装删除插件、白苹果、无限重启、蓝屏等问题时，由于无法使用电脑访问手机而解决不了。
所以，安装必备插件非常重要！
**必备插件列表及安装方法见下一章节。**

###5. 删掉爱思助手安装PP助手
> 把爱思助手自动安装的App 删掉，对比过iTools/3K助手/同步推/PP 助手等几个同类下载越狱软件的应用后，不管是软件更新速度还是丰富程度，PP助手都是最好的。
添加软件源apt.25pp.com, 安装PP助手。


##越狱必备插件

###Cydia Substrate
> **安装方法**
打开Cydia直接搜索，一般输入前两个单词就能找到了，认准Bigboss 源的。
**插件功能**
很多越狱插件的依赖插件，尤其是需要较高系统权限的模拟点击类辅助工具，比如：触动精灵。

###Apple File Conduit "2"
> **安装方法**
打开Cydia直接搜索，一般输入前两个单词就能找到了，认准Bigboss 源的。
**插件功能**
手机连接电脑后显示越狱系统文件。

###Appsync
> **安装方法**
添加 AppSync 官方源 cydia.angelxwind.net，在插件分类中找到 AppSync Unified,详情页右上角点击安装
**插件功能**
越狱后安装非App Store来源的ipa 文件也就是破解应用需要。

###远程命令控制 OpenSSH

> **安装方法**
打开Cydia直接搜索。
**插件功能**
触动精灵企业版中控、putty 等工具连接设备都需要这个插件，强烈建议安装。有些插件卸载不掉或者Cydia 闪退等很多疑难问题有时候都需要借助此插件解决。

###文件管理工具 iFile
> **安装方法**
打开Cydia直接搜索，认准Bigboss 源的。
**插件功能**
打开Cydia直接在手机上查看文件路径和权限。
**使用方法**
先选择语言，设成简体中文。
有文本编辑和图片浏览功能。
**注意事项**
deb 安装包直接点击即可选择安装，需要注意的是deb 包安装成功后需要重启设备。

##其他常用插件
###屏蔽无 SIM 卡提示 noNoSimAlert8
> **安装方法**
打开Cydia直接搜索，认准Bigboss 源的。
**插件功能**
屏蔽每次没插卡的手机重启后弹出插卡提示的窗口。
**注意事项**
触动精灵企业版已内置此插件，无需再次安装。

###显示点击位置 TouchPose+
> **安装方法**
打开Cydia直接搜索，认准 Bigboss 源的。
**插件功能**
在屏幕上当前点击位置显示一个圆点。

###内购破解 IAPCrazy
> **安装方法**
官方源：apt.youyuanapp.com
**插件功能**
内购某些应用或者游戏时，绕过付费验证。


##安装 deb 插件

###ifile
>  1. 如果身边没有数据线，强烈推荐使用 iFile Wifi 传输
 2. 打开iFile，点击齿轮按钮设置，将语言设成简体中文并重启程序
![ifile3.png-60.3kB][13]
 3. 点击iFile 底部的网页服务器（小地球标志）
![ifile.png-9.8kB][14]
 4. 在电脑上打开任意浏览器并在地址栏输入 192.168.1.xx:10000(iFile 界面上显示的那个地址）
![ifile2.png-113.9kB][15]
 5. 将 deb 安装包拖到浏览器的路径下进行导入，等待进度条完成即可（导入文件也可以 使用iTools/PP助手/iFunbox/爱思助手等）
 6. 找到deb 文件，单击，在弹出窗口选择安装程序（这一步可以用SSH 命令完成，参考 putty 部分）
 ![ifile4.png-80kB][16]
 7. 查看安装日志，返回值是否是 0（如果不是 0 说明安装失败了）
 ![IMG_0011.PNG-118.3kB][17]
 8. 安装完成后，重启手机（非常重要！！！）


###SSH 命令
> - 前提是已安装越狱插件 OpenSSH

**发送本地文件到设备：**
详细请百度 scp 命令，我没用过，所以不会，哈哈哈

**安装 deb 文件：**
```
dpkg -i /var/root/Media/test.deb -- 注意空格
--安装 /var/root/Media/ 目录下的 test.deb
```

###安装常见问题
> 如果是用 ifile 进行 deb 的本地安装，安装完成后的返回值不是 0，就代表安装失败了。

####Trying to overwrite/返回值：256
<center>![image.png-338.3kB][18]</center>
<center>*本地安装*</center>
<center>![2.png-236.1kB][19]</center>
<center>*跨源安装*</center>
**错误提示**
> Trying to overwrite 应用包名，which is also in package

**现象**
> 安装完成后桌面没有出现插件图标。

**出现原因**
> 覆盖安装出错，多半出现在升级软件过程中。本地已经安装了要安装的插件或者插件自带的依赖插件，导致冲突。

**解决方法**
> 请先卸载掉错误提示中软件。同时使用盗版源，镜像源由于软件标识混乱经常造成这样的问题。
有时候虽然两个包名不一样，但实际上是同一个插件，在使用第三方源（如威锋源）安装插件后再去官方源安装时很容易遇到这个问题。

####no space left/failed in buffer_write(fd) (7,ret=-1）
<center>![image.png-20.6kB][20]</center>

**现象**
> 新越狱的手机还没安装几个插件，在安装新插件过程中结束了，安装失败。

**出现原因**
> 这个提示在非完美越狱或 iOS9 以上的越狱设备上经常出现，这是由于 iOS 设备对系统容量做了限制造成的。iOS 9 以上规定系统文件最多可以占用 3G 容量，而越狱文件和越狱插件都是安装在系统目录的。

**解决办法**
> 卸载不常用的越狱插件，节省系统容量。




##越狱平刷
###平刷工具 Cydia Eraser
> **安装方法**
打开Cydia直接搜索。
**插件功能**
恢复设备到未越狱纯净状态，修复文件损坏问题。
> 冬青鼠(iILEX RAT,适用于 iOS 4-6)和 Semi-Restore 仍将提供下载。
然而，本插件和以上两个的区别在于：在恢复完成后，所有的文件损坏或丢失都会被修复到初始且未越狱状态。
**为什么选择本插件？**
有两类人会需要这个插件：
1. 你想要把手机卖掉并且不想升级到最新系统来抹掉所有个人信息，能越狱的系统能卖个更好的价钱。
2. 手机设置出了问题，你尝试了各种办法仍未解决，想要恢复到纯净状态重新越狱。

###电脑平刷工具 SemiRestore
> - 如果遇到三无（AFC 插件、OpenSSH、ifile）手机，无法安装 Cydia Eraser,或者 Cydia Eraser 刷机无效、重新越狱也失败的情况，可以试试另外一种平刷工具。
- SemiRestore 是一款在 PC 电脑上使用的平刷工具，支持 iOS 5 - 9.2 的越狱系统进行平刷。点击下载：![SemiRestore9-Windows-1.0.4.zip-1212.8kB][21]
 - 手机连接电脑，需要确保电脑上已经安装了 iTunes。
 - 打开软件，点击右侧按钮开始，直到绿色进度条走完.。 - 期间手机会自动重启很多次，在平刷成功前不要对手机进行任务操作。

<center>![image_1b6e26g5k1i901h9doap1erf1tta12.png-116.1kB][22]</center>


##第三方文件管理工具
> **iTools/PP助手/爱思助手/iFunBox**
个人推荐iTools,用过了这么多助手类工具，当其他助手识别不了手机的时候，iTools 还好好的，界面也比较简洁。最常用的手机截图、重启、文件操作、实时屏幕等也很好用，另外一个很重要的理由就是其他的助手游戏安装包都是自己封装过的，太闹心。
当然建议大家最好是装两个助手，一个不能用了至少还有另一个备用。

<center>![itools-1.png-121.8kB][23]</center>

> - **手机截图**
在iTools 的首页界面，手机下方最左侧的按钮。
值得注意的是，要想直接在电脑上给手机截图，需要安装一个开发者插件，这个插件呢，有的手机是死活也装不上的。如果遇到这种情况，你就放弃吧。老老实实地在手机上截图然后相册导出。
截图可以设置是否包含手机壳，仅复制到剪切板或者保存文件到本地。
- **重启**
一键重启
- **文件管理**
![QQ截图20160525105936.png-19.3kB][24]
 -  **文件系统：用户系统** 触动精灵、帮你玩、企业版、小精灵的文件都会显示在这里，也就是说脚本目录、资源目录和配置文件目录所在。
 - **文件系统：越狱系统** 这里显示了所有系统文件夹。
 - **程序（系统）** 系统自带程序和deb 格式的插件程序。如果遇到卸载不掉的插件程序，可以直接删除插件的文件夹然后重启设备即可。
 - **程序（用户）** 用户自行安装的ipa 格式应用程序。

###iOS 文件系统常用路径
> /private/var/mobile/Applications/ **应用安装路径**
/private/var/keychains/keychain-2.db  **keychain数据库**
/private/var/keybags/systembag.kb
/private/var/log/syslog **日志文件**
/private/var/mobile/Library/Keyboard/dynamic_text.dat **键盘缓存**
[app-home]/Library/Caches/Snapshots **应用屏幕快照**
/Library/MobileSubstrate/DynamicLibraries/ **dylib注入放置地方**
/System/Library/LaunchDaemons/ **开机自动启动配置文件放置地方**
 /private/var/root/Media/Cydia/AutoInstall/ **Cydia自动安装文件夹**

##越狱进阶：远程控制
> 有时候遇到手机有一些莫名奇妙的原因打不开 Cydia 了，但是还是越狱状态，就可以远程登录进手机系统进行一些操作来解决问题。
首先你的越狱手机上必须装了 OpenSSH 工具，但是，iOS10 是不需要安装的，借助第三方工具的打开 SSH 隧道功能即可远程连接。

###SSH 连接工具：Putty
> 下载链接见附录。

<center>![QQ截图20160525110804.png-39.7kB][25]</center>

###使用方法
>  1. 打开程序，输入手机的IP地址（例如：192.168.1.100）
 2. 不要修改其他的任何信息，点击Open按钮
 3. 在弹出的窗口中选择【是】
<center>![QQ截图20160525111059.png-27.4kB][26]</center>
 4. 在弹出的黑色输入框内显示login as:,输入root,回车
 5. 接着显示 root@手机IP地址's password:,输入默认密码 alpine 并回车。这里需要注意的是当你输入密码的时候输入框是没有任何反应的，不会显示你输入的字符，请不要在意。
 6. 当弹出 设备名:~root# 文字时，说明你登陆成功，可以输入命令行对手机进行操作了。
<center>![QQ截图20160525111125.png-21.4kB][27]</center>

###root 密码不是 alpine
> 有时候会遇到买的二手机器 root 密码被修改的情况，或者自己改过但是不记得了，下面是用第三方文件管理工具修改 root 密码的方法供大家参考。
root 密码文件存放位置：/etc/master.passwd

**具体步骤**
> 1. 用 iFile 或者其他第三方文件管理工具的文本编辑功能打开 master.passwd 文件
2. 你会找到类似这样的一行字符——root:`UlD3amElwHEpc`:0:0::0:0:System
3. 阴影部分就是加密过的密码
4. 把它替换为 `smx7MYTQIi2M`，这是对应的密码就是 alpine
5. 保存，重启。

###常用 SSH 命令

>  1. 删除软件包（保留其配置信息）
命令行：dpkg -r package
示例：dpkg -r com.touchsprite.ios(注意空格和包名）
 2. 删除一个软件包（包括配置信息）
命令行：dpkg -P package
示例：dpkg -P com.touchsprite.ios(注意空格和包名以及大小写）
 3. 显示软件包的版本号
命令行：dpkg –version package
示例：dpkg -version com.touchsprite.ios(注意空格和包名）
 4. 显示所有已经安装的Deb包，同时显示版本号以及简短说明
命令行：dpkg -l
 5. 重启设备
命令行：reboot
<center>![image_1at2o1vnp94a1sl7fht1bnn3tf9.png-37.9kB][28]</center>


##越狱疑难问题
####手机不停重启
> 如果不小心在触动精灵开机自动运行脚本里写了重启代码或者安装了冲突插件导致设备不停重启，可以试试同时按住电源键和Home 键强制关机，然后同时按住音量+和电源键启动手机，用这种方式开机不会加载越狱插件启动触动服务。

####iOS9/10 No Space Left 系统容量不足
> 这是由于 9.0 以上系统限制了系统文件所占容量，而越狱插件都算作是系统软件，导致系统文件超过限制。
建议不要安装过多无用的越狱插件。
iOS 的容量也就是相当于电脑的硬盘空间分为两部分：系统空间和非系统空间（数据空间）。
Cydia 越狱文件和越狱后安装的 deb 插件都存储在系统空间，而从 App Store 下载安装的 ipa 应用存储在数据空间。
<center>![image.png-9.1kB][29]</center>
而 iOS 9 以上系统对于系统容量上限做了限制，也就是说 Cydia 可安装插件剩余的空间变小了，甚至只能装几个插件就会提示满了。

####插件卸载不掉
<center>![applicatons.png-49.8kB][30]</center>
> 有时候有些插件卸载会各种报错导致卸载进程中断，这个时候可以通过删除程序目录的方法强制卸载。
手机连接 PP 助手，访问目录 文件管理 -> 常用目录 -> 应用程序（越狱），找到要卸载的插件的文件夹名字，右键删除，重启手机。
需要注意的是，这个路径下都是系统应用或者越狱插件，请千万确认再进行操作，否则很容易导致手机白苹果。
另外就是删除文件夹之后，一定要重启手机。

####安装插件后桌面没有图标
<center>![image.png-45.2kB][31]</center>
> 首先需要说明的是，不是所有的越狱插件都有图标的，比如 AFC2、Cydia Substrate 就是没有的。
触动精灵、iFile 这种如果在 Cydia 已安装列表里显示已安装，但是桌面却没有图标的，才算异常。
解决办法就是，重新安装 UIKit Tools 插件，在 Cydia 里搜索或者已安装列表专业人士界面可以找到。

##获取应用 Bundle ID
###越狱插件
<center>![image_1b408k72a1gp9100a14i44ib1nn79.png-221.7kB][32]</center>
> - 触动精灵更多界面可以查看 ipa 应用的 Bundle ID, 下面介绍下如何获取越狱应用的 Bundle ID
 - 打开 Cydia -> 打开已安装界面 -> 找到越狱插件 -> 点击查看插件详情页面 -> 滑动到页面最底部就可以看到该插件的 Bundle ID 了
 - 不管是搜索还是从源里找到插件的详情页也可以查看该插件的 Bundle ID

###系统应用和 ipa
<https://www.zybuluo.com/miniknife/note/212706#函数frontappbid-获取前台应用>
这个方法适用于任何应用获取 Bundle ID

首先在触动精灵中创建脚本，代码如下
```lua
bid = frontAppBid()
mSleep(1000)
dialog(bid)
```
打开要获取的应用，运行脚本，弹出提示窗口显示的就是该应用的 Bundle ID

使用 iFile、PP助手等软件可查看应用文件夹下的 Info.plist，其中的 `CFBundleIdentifier` 即为该应用的 Bundle ID


##Cydia 常见问题
> 日常使用 Cydia 时，经常会出现一些问题，导致 Cydia 软件无法安装，并且 Cydia 会提示一行红字或者黄字。
通常情况下，黄字代表一些警示型的错误，此时问题不大，一般情况下不影响 Cydia 运行。
若提示红字的话，就代表 Cydia 出现了重大问题，可能影响 Cydia 正常运行或者无法安装软件。
日常使用 Cydia，大概有 60% 的问题都是因为网络因素造成的，所以大家使用的时候尽量用稳定高速的 Wi-Fi。
同时我们也尽量少使用破解源，镜像源等容易造成冲突的cydia源，选择高速稳定 Wi-Fi，同时尽量避开高峰时段下载软件，每次打开 Cydia 耐心等待上方刷新提示不要急于点击取消，一般就不会出现莫名其奇妙的问题。
下面列出一些我遇到过但是百度没找到有效的解决办法的例子，在这里不得不说，技术性的问题有时候还是要谷歌一下才行啊！

###搜索插件，右上角不显示安装一直在转圈
> 比如 iFIle，每次搜索安装，右上角都不显示按钮，后来偶然发现，锁屏再解锁或者把 Cydia 退出到后台，就可以了。

###Cydia 闪退/图标不见了/安装任何插件都报错 Debian Packager
> 这个多半是因为某个程序安装或卸载时导致状态异常，Cydia 启动不起来造成的。
网上说的卸载Cydia 重新安装什么的都试过了完全不起作用，另外千万不要轻易尝试卸载Cydia!
首先，确保你的手机上安装了Apple File Conduit 或者 iFile，如果安装了openSSH 就更好了。
然后回忆下你最近安装或更新过的插件，在程序（系统）中找到这个插件的文件夹，删除。
当然如果你不记得是哪个插件，也可以用下面的方法找出来

> 把手机连上电脑，打开 iTools 或 PP 助手,找到的路径private/var/lib/dpkg/status，将status 文件导出到电脑

![image.png-130.1kB][33]
> 用文本编辑器打开status 文件，从上往下浏览，找到 status 状态不是 install ok installed 的
如果是安装插件提示错误，也可能是文件出问题了，把 status 删掉，把 status-old 重命名为 stauts,重启 Cydia

![QQ截图20160524190054.png-26.8kB][34]
> 在程序（系统）中找到状态异常的程序.app 文件夹,选中删除，重启设备

![QQ截图20160524190457.png-43kB][35]
> - 重启完成后 Cydia 大概就能打开不会闪退了，但是你可能看到你刚才删除的程序没有卸载干净
- 在电脑上打开putty,用dpkg -P + Package 命令卸载即可，[putty 的使用方法][36]
- 如果 Cydia 不见了或者仍然闪退，还可以试试从同样系统的越狱手机上复制一份 Cydia.app 覆盖到有问题的手机上，重启手机也可能修复这个问题。

###无论怎么刷新软件源都不显示某个软件包
> 比如在触动官方源里，可以看到帮你玩但看不到触动精灵，这个时候你就需要看一下已安装里是不是已经存在别的源或者本地 deb 安装的触动精灵了。
Cydia 有一个规则就是如果你已经从其他源或者本地安装了一个软件，那么包含了同名（package name/bundle ID）安装包的源将不再显示此安装包。

###Cydia 源不显示软件包/已安装界面空白
> 发生这种情况时，一般还会出现提示“XXX package need to be reinstalled, but can't find archive for it”。
这是由于安装包安装失败导致文件损坏或配置错误出现的问题，解决办法就是按照上面的方法找到 status 文件，保存到电脑，用 notepad++ 打开，将提示中的文件包名部分内容删掉。再将status 文件导入覆盖原来的，重启 Cydia,已安装界面就正常了。

###dpkg locked
> 越狱环境损坏造成部分插件无法安装，解决办法：搜索下载 AFC2 插件

###dpkg: error: dpkg status database is locked by another process
> 用 deb 直接安装插件时可能会遇到此错误，找到 /var/lib/dpkg/路径下的 lock 文件删掉即可。

###Sub-process /usr/libexex/cydia/cydo returned an error code (2)
> 很多人都是在刚刚越狱完成后要更新插件时遇到的这个错误，也有人是重启设备之后忽然就不行了，安装卸载插件都会报错，大部分还会伴随 AutoInstall 也失效的问题。
这个时候，如果安装了AFC2 或者 iFile，可以把 var/lib/dpkg/updates 路径下的文件全部删除，重启手机试试。
当然如果你的手机上这两个插件都没安装，OpenSSH 插件也没有，手机基本也就废了。

###Counld not perform immediate configuration
**错误提示**
> Counld not perform immediate configuration on already unpacked '报错插件包名'. Please see man 5 apt.conf under APT::Immediate-Configure for details.
![QQ图片20160504181614.png-22.1kB][37]

**解决方法**
>  1. 在putty 使用dpkg -configure -a 命令重新配置应用
 2. 重新安装报错的插件

###package missing
**错误提示**
> dpkg: serious warning: files list file for package "报错插件包名" missing, assuming package has no files

**解决方法**
>  1. 在putty 用dpkg -r 和 dpkg -P 卸载报错插件并清除相关信息
 2. 在putty 使用dpkg -configure -a 命令重新配置应用

###Fail to fetch/POSIX: Operation timed out/Host unreachable/Request timeout
**错误提示**
> “Failed to fetch http://Cydia.zodttd.com/repo/Cydia/dists/stable/Release.gpg Bad URL ”
“http://repo666.ultrasn0w.com/./zh_CN.bz2 POSIX:Socket is not connected ultrasn0w ”
“http://apt.thebigboss.org/repofiles/Cydia/dists/stable/Release.gpg POSIX:Socket is not connected ”
POSIX: Operation timed out

**出现原因**
出现这种情况的原因是 Cydia 无法连接到原服务器，出现这种问题的原因主要有以下两种：
> 1. 源服务器坏掉了（解决办法：稍后再试）
2. 网络传输问题

**解决方法**
> 对于原因 1，确实没有办法，可以等一等稍后再试。
对于原因 2，可以换一个更加稳定快速的 Wi-Fi 连接。当然也不排除是由于服务商的问题，比如有网友发现使用中国移动的网络（包括 CMCC 接入点的 Wi-Fi），由于移动的网络策略，屏蔽了许多国外的 Cydia源。

###I wasn’t able to locate file for the app
**错误提示**
> I wasn’t able to locate file for the app.this might mean you need to manually fix this package.

**出现原因**
> 安装包下载不完整，当然也有可能此deb安装包本身是否有问题。

**解决方法**
> 排除安装包问题的情况下，请完全退出 Cydia（完全退出可清理缓存），再次打开 Cydia刷新下软件列表，然后再次安装这个软件，一般问题都可以得到解决。



###Hash Sum mismatch
**错误提示**
> Hash Sum mismatch

**出现原因**
> 下载的 deb文件的 md5 和 Packages 文件不同造成的问题。
当然也有可能因为 Cydia 源的问题导致 deb文件 md5 和验证 md5 不同。

**解决方法**
> 清空 Cydia 缓存目录： /var/cache/apt/archives 然后再试。

###Size mismatch
**错误提示**
> Size mismatch

**出现原因**
> 1. Cydia没有刷新完成，新旧版本对照不符
2. 网络质量不好
3. Cydia软件源出现了问题或者使用了镜像源

**解决方法**
> 先删除出现问题的源，然后回到Cydia主界面，打开更多软件源，再把 BB 源添加回来。这样做的目的就是清理Cydia原有的源列表，重新添加即可完全更新 Packages 文件，修复了 Cydia 源的问题。

###HTTP/1.1 500 Internal Server Error
**错误提示**
> HTTP/1.1 500 Internal Server Error

**出现原因**
> 源服务器内部服务器错误无法做出相应。

**解决方法**
> 这种情况发生在刚刚完美越狱发布时候，这时大量访问让 Cydia源服务器不堪重负因此被流量压垮。一般过阵子再试就好了。

###HTTP/1.0 403
**错误提示**
> HTTP/1.0 403 This packages is either paid or requires a paid package to function.If you paid :contact saurik@saurik.com for help.If not,purchase the original package.

**出现原因**
> 您正在下载一个需要付费的 Cydia软件.

**解决方法**
> 请支付后再下载。

###Root directory’s space is not enough
**错误提示**
> Root directory’s space is not enough

**出现原因**
> iPhone 、iPad 空间容量不足

**解决方法**
> 请删除些软件或文件再次尝试下载。

###Some index files failed to download
**错误提示**
> Some index files failed to download,they have been ignored,or old ones used instead.

**出现原因**
> 网络不稳定

**解决方法**
> 下载 Packages 时出现问题，可以尝试重新刷新源。

###NetDB: Open nodename nor servname
**错误提示**
> NetDB: Open nodename nor servname provided, or not known

**出现原因**
> 网络不稳定

**解决方法**
> 在设备设置里关掉 Wi-Fi 开关，然后在通用 - 还原 - 选择还原网络设置。

###半安装包，Cydia 变更和已安装界面空白
**错误提示**
> 某个程序为半安装状态
或者红字提示该程序无法删除，需要手动修复

**解决方法**
在弹出半安装状态提示时点击卸载清除该程序


  [1]: http://tihmstar.net/etasonjb/
  [2]: http://wall.supplies/
  [3]: http://jailbreak.me/
  [4]: https://phoenixpwn.com/
  [5]: https://iabem97.github.io/saigon_website/
  [6]: https://h3lix.tihmstar.net/
  [7]: https://g0blin.sticktron.net/
  [8]: https://yiqixie.com/
  [9]: http://static.zybuluo.com/lisaisacat/8q73g9uq22nl1e40sl6o84gf/image.png
  [10]: http://static.zybuluo.com/lisaisacat/1tc0q2qjicigxzg213ah8nkz/image.png
  [11]: http://static.zybuluo.com/lisaisacat/76sicfp7sd7gpctuxrttuadz/image.png
  [12]: http://static.zybuluo.com/lisaisacat/x03u1qz3wwlc7wvl7yj4tyfq/%E5%BF%BD%E7%95%A5%E6%9B%B4%E6%96%B0.png
  [13]: http://static.zybuluo.com/lisaisacat/lpix95o8id6lespkz9pf1z7h/ifile3.png
  [14]: http://static.zybuluo.com/lisaisacat/qpy5credokqpkqybmaysxo8l/ifile.png
  [15]: http://static.zybuluo.com/lisaisacat/h02tpik6axzj5hkhnvc2a9wc/ifile2.png
  [16]: http://static.zybuluo.com/lisaisacat/jxenccspgew2k7am0kmg1zav/ifile4.png
  [17]: http://static.zybuluo.com/lisaisacat/9h7m7shbhxqol7ykzqooi7o8/IMG_0011.PNG
  [18]: http://static.zybuluo.com/lisaisacat/gqhw52882lfwucgu9fvf8dya/image.png
  [19]: http://static.zybuluo.com/lisaisacat/fi1is1nrotex6rzbc5zb54ka/2.png
  [20]: http://static.zybuluo.com/lisaisacat/5eslpd5kaalnutl6amczsxfi/image.png
  [21]: http://static.zybuluo.com/lisaisacat/jz2kjpst83usgypaa0c38rxt/SemiRestore9-Windows-1.0.4.zip
  [22]: http://static.zybuluo.com/lisaisacat/xbn6pvzufdpyybzdo5gt81vo/image_1b6e26g5k1i901h9doap1erf1tta12.png
  [23]: http://static.zybuluo.com/lisaisacat/rvx2o86vpnwxjw1dk6xa4lfr/itools-1.png
  [24]: http://static.zybuluo.com/lisaisacat/45v1oelss9lkxbkoas3nties/QQ%E6%88%AA%E5%9B%BE20160525105936.png
  [25]: http://static.zybuluo.com/lisaisacat/xalllituypll4k58igf6ug22/QQ%E6%88%AA%E5%9B%BE20160525110804.png
  [26]: http://static.zybuluo.com/lisaisacat/1muelwwtybo3y1roqqf28ou3/QQ%E6%88%AA%E5%9B%BE20160525111059.png
  [27]: http://static.zybuluo.com/lisaisacat/n7fozvg2wvymtv0d4a8phqf0/QQ%E6%88%AA%E5%9B%BE20160525111125.png
  [28]: http://static.zybuluo.com/lisaisacat/9j5qei490vhiccnapq3ta9r0/image_1at2o1vnp94a1sl7fht1bnn3tf9.png
  [29]: http://static.zybuluo.com/lisaisacat/alwogaa9kje8xeebjwo5yx7m/image.png
  [30]: http://static.zybuluo.com/lisaisacat/ytik9ox1izwc2ocex21u77op/applicatons.png
  [31]: http://static.zybuluo.com/lisaisacat/orr5fayvd0rmc1n6nzr27brr/image.png
  [32]: http://static.zybuluo.com/lisaisacat/2f7qzo44fxhb0princwojs4a/image_1b408k72a1gp9100a14i44ib1nn79.png
  [33]: http://static.zybuluo.com/lisaisacat/7z1qbygn6win9q3af69sdbwl/image.png
  [34]: http://static.zybuluo.com/lisaisacat/wbw4h9ghnamei8fz4mneshmc/QQ%E6%88%AA%E5%9B%BE20160524190054.png
  [35]: http://static.zybuluo.com/lisaisacat/9xqkw06od5pos7xrjm38akxs/QQ%E6%88%AA%E5%9B%BE20160524190457.png
  [36]: https://zybuluo.com/lisaisacat/note/324664#ssh-%E8%BF%9E%E6%8E%A5%E5%B7%A5%E5%85%B7putty
  [37]: http://static.zybuluo.com/lisaisacat/g9rum0npyzolxea4r217v529/QQ%E5%9B%BE%E7%89%8720160504181614.png