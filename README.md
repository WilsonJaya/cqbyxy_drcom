# 重庆建筑科技职业学院宽带登录Python版
本项目为重庆建筑科技职业学院（原重庆房地产职业学院）宽带（dr.com/哆点）登录Python版  
本项目参考[Drcom-generic](https://github.com/drcoms/drcom-generic)，有兴趣可以自己弄。
## 所需环境
[python3.9](https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe)(点击下载，截至20201104最新版)
>你也可以自行访问[python](https://www.python.org/downloads/windows/)官网下载最新版
## 程序说明
|文件|说明|
|:-|:-|
|Drcom-cqbyxy-python3.py|主程序(python2版本请用Drcom-cqbyxy-python2.py)|
|start_show.bat|前台运行|
|start_hidden.vbs|后台运行|
|stop_all_python.bat|停止运行 **注意：这会终结掉所有正在运行的Python程序**|

## 程序使用
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
