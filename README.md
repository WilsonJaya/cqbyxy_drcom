# 本项目为重庆建筑科技职业学院宽带登录Python版
本项目参考[Drcom-generic](https://github.com/drcoms/drcom-generic)，有兴趣可以自己弄。
## 程序说明
---
1. Drcom-cqbyxy-python3.py----主程序
_python2版本请用Drcom-cqbyxy-python3.py_
---
2. start_hidden.vbs----后台运行
---
3. start_show.bat----前台运行
---
4. stop_all_python.bat----停止运行
_注意：这会终结掉所有运行Python程序_
## 程序使用
修改drcom.py中的`username`,`password`,`mac`,其他不要动。
```
server = "172.16.10.2"
username = "account number" #你的宽带账号
password = "passwd" #你的密码
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
