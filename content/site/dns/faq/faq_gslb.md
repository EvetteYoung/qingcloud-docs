---
title: "GSLB 常见问题"
description: 本小节主要介绍 GSLB 常见问题。 
keywords: gslb faq 
weight: 20
collapsible: false
draft: false
---



## GSLB 如何判断应用服务故障？

QingCloud GSLB 集成了应用服务监控，可以采用多个监控点组合报警的形式作为服务整体异常判断条件。

用户可以选择使用 TCP 或 HTTP 方式对应用服务进行监控，判断应用服务是否故障。

- TCP 监控：可以根据 TCP 端口的响应时间来判断应用服务是否故障。

- HTTP 或 HTTPS 监控：可以根据 HTTP 或 HTTPS 响应时间、返回码信息来判断应用服务是否故障。

## GSLB 支持哪些访问路线？

GSLB 可根据不同地域的访问者来设定不同路线。
    
主访问路线为设置的第一条解析线路，默认为**全网默认**。

设置子解析路线可选择**中国电信**、**中国移动**、**中国联通**、**中国教育网**、**大陆其他运营商**、**搜索引擎**、**港澳台及海外**。
