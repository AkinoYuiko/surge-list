# 配置示例

```config
[General]
proxy-test-url = http://1.1.1.1/
internet-test-url = http://taobao.com/
geoip-maxmind-url = https://github.com/AkinoYuiko/geoip/raw/release/Country.mmdb

[Proxy Group]
Proxy = select, policy-path=订阅链接

[Rule]
RULE-SET,https://github.com/AkinoYuiko/surge-list/raw/main/boost.list,Proxy
RULE-SET,LAN,DIRECT
GEOIP,CN,DIRECT
FINAL,Proxy
```
