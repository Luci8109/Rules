DOMAIN-SUFFIX：域名后缀匹配

DOMAIN：域名匹配

DOMAIN-KEYWORD：域名关键字匹配

IP-CIDR：IP 段匹配

SRC-IP-CIDR：源 IP 段匹配

GEOIP：GEOIP 数据库（国家代码）匹配

DST-PORT：目标端口匹配

SRC-PORT：源端口匹配

PROCESS-NAME：源进程名匹配

RULE-SET：Rule Provider 规则匹配

MATCH：全匹配

TIP

使用PROCESS-NAME需要 Clash for Windows v0.11.5 及以上版本；规则需要匹配完整的进程名（包括可执行文件后缀）方可生效；该规则不适用于 TAP 流量

用户界面暂不支持添加RULE-SET规则，请手动编辑配置文件

MATCH需要位于规则列表末尾
