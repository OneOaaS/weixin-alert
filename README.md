# weixin-alert
使用方法见微信公众号
http://url.cn/4A37R4z

# 脚本位置:
```
wget https://raw.githubusercontent.com/OneOaaS/weixin-alert/master/weixin_linux_amd64
cp weixin_linux_amd64 /etc/zabbix/alertscripts/weixin
chown 755 /etc/zabbix/alertscripts/weixin
chown zabbix:zabbix /etc/zabbix/alertscripts/weixin
```

# 脚本测试
```
/etc/zabbix/alertscripts/weixin --corpid=wxee***********81aa --corpsecret=Mm0mHwI8iVsjA*JUGySxOFMIlbosoVEkWIEiw --msg="您好</br>告警测试" --user=oneoaas --agentid=1000003
返回数据:
{"errcode":0,"errmsg":"ok","invaliduser":""}
```

