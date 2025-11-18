防DNS泄露 大佬自用配置

参考https://linux.do/t/topic/1061825/1 mihomo 内核极简防 DNS 泄漏配置（2025 年）

自带覆写功能的客户端，如 Clash Party/Sparkle 
可以直接进行覆写

也可以自行设置 DNS覆写规则，参考如下

IPV6 打开

连接遵守规则 打开

域名映射规则 取消映射

基础服务器 

tls://223.5.5.5

tls://223.6.6.6

默认解析服务器

https://cloudflare-dns.com/dns-query

https://dns.google/dns-query

直连解析

https://dns.alidns.com/dns-query

https://doh.pub/dns-query

代理节点解析

https://doh.pub/dns-query

https://dns.alidns.com/dns-query
