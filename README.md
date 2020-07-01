# 中弘空调网关 API
### 地址: [http://xx.xx.xx.xx/cgi-bin/api.html]()

##  1. 查询空调状态列表
f=17&p=[0-n]

## 2.修改空调名称
f=19&idx=n&nm=xx


nm: 1楼
f: 14
ia: 0
oa: 0
idx: 0
mask: 0f


f=1，获取产品信息
f=2，获取网络设定
f=3，修改网络设定
f=4，修改远程设置
f=5，获取时间
f=6，修改时间设置
f=7，
f=8，
f=9，获取RS485设置
f=10，修改RS485设置
f=11,获取主机设定
f=12,修改主机设定
f=13,获取群组配置;p=[0-n],页码
f=14,修改群组配置
f=17,获取空调列表;p=[0-n],页码

f=19,修改空调名称;idx=x,主机编号;nm=n,名称


f=21,修改空调属性;OnoffLock: 1
tempLock: 0
highestVal: 26
lowestVal: 26
modeLock: 0
idx: 0


f=22,获取KNX设置
f=23,修改KNX设置
