# 重庆建筑科技职业学院宽带登录Python版
本项目为重庆建筑科技职业学院（原重庆房地产职业学院）宽带（dr.com/哆点）登录Python版  
本文档还未完善，摸鱼中。。。。
## 1.  所需环境
1. windows系统(Windows 7,Windows 10均测试通过，其他windows版本自测，理论能安装python都可以)
2. [python 3.9](https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe)(截至2020-11-04最新版)
>你也可以自行访问[python](https://www.python.org/downloads/windows/)官网下载最新版
3. 经过测试只要可以安装python环境都可以成功运行
## 2.  程序说明
|文件|说明|
|:-|:-|
|Drcom-cqbyxy-python2.py|主程序,python2.x版本|
|Drcom-cqbyxy-python3.py|主程序,python3.x版本|
|start_show.bat|前台运行|
|start_hidden.vbs|后台运行|
|stop_all_python.bat|停止运行 **注意：这会终结掉所有正在运行的Python程序**|

## 3.  程序使用
修改drcom.py中的`username`,`password`,`mac`,其他不要动。
```
server = "172.16.10.2"
username = "account number" #你的宽带账号(默认为你在学校办的手机号)
password = "password" #你的密码(18级以前的为身份证后6位，19级及以后的为手机号后6位)
host_name = "fuyumi"
host_os = "Windows 10"
host_ip = "172.21.22.251"
PRIMARY_DNS = '218.201.4.3'
dhcp_server = '172.16.10.2'
mac = 0x00e0704e06bb #你的MAC地址
CONTROLCHECKSTATUS = '\x20'
ADAPTERNUM = '\x04'
KEEP_ALIVE_VERSION = '\xdc\x02'
```
### 3.1  Windows下使用
首先你得安装python已经安装的跳过此步  
先去[python官网](https://www.python.org)下载python，或者你也可以使用我提供的已经测试过的版本[点我下载]()
![about](https://user-images.githubusercontent.com/2252500/30239658-3e20747e-9594-11e7-8a97-5227050bfedd.png)
安装完成后测试win+r输入CMD回车进入命令行模式，输入python，看是否有提示
### 特别感谢
---
本项目参考[Drcom-generic](https://github.com/drcoms/drcom-generic)
同时，也离不开许多同学的测试，这里不再一一列举。
## 许可证

AGPLv3

特别指出禁止任何个人或者公司将 [drcoms](http://github.com/drcoms/) 的代码投入商业使用，由此造成的后果和法律责任均与本人无关。 
