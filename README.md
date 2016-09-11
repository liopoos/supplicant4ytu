# 重要说明 #
这是由lyq1996开发的基于Python的安腾小蝴蝶的全平台认证脚本。

源地址：https://github.com/lyq1996/supplicant

目前我修改了部分源代码用来供**烟台大学**的赛尔网络认证使用。
其他学校可能会认证失败。

详细介绍：https://blog.mayuko.cn/archives/1897

#测试环境#
* OS X、windows、linux、android、(Openwrt以测试，需要python运行环境，/overlay需要8m以上可用空间)
* Python 2.7.x


# 已知bug #
若认证成功后关闭终端后再次认证则会出现time out。

**修复方法：**

关闭终端，等待赛尔网络掉线后再次连接即可。

# 使用前的配置   #
使用前请配置Python2.7.x，对于一些自带Python3.5的linux发行版本用户请自行配置2.7，否则会报错。  
在程序打开前必须先打开.py文件进行用户名，密码的填写。  

Mac用户推荐使用coderunner打开下载的py文件  

安卓在使用前请下载Qpython。

username = '' #在这里填上你的用户名

password = '' #在这里填上你的密码


# 运行步骤 #
上线：  
Mac用户：打开终端，把py文件拖到终端里，回车。  
Linux用户：下载python运行环境，随后步骤同Mac。    

下线：  
输入ctrl＋C

# 注意事项   #
使用时请看好你的网卡mac地址和程序显示的是否一致，以及ip是否是当前网卡上的。  
请使用ifconfig命令选择网卡，否则会报用户绑定Mac地址错误！  

如果终端显示权限不够，则右键属性，将**允许作为可执行文件**选中即可。

  

