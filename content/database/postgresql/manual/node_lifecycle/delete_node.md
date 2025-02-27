---
title: "删除节点"
description: 本小节主要介绍如何删除 PostgreSQL 节点实例。 
keywords: PostgreSQL 节点删除；删除节点
weight: 15
collapsible: false
draft: false
---


本小节主要介绍如何删除 PostgreSQL 集群节点。

> **注意**
> 
> 删除节点为危险操作，请谨慎操作。
> 
> 删除节点过程中节点状态将切换为**更新中**，不支持集群其他生命周期操作。

## 约束限制

- `基础版`集群不支持删除节点。
- 不支持删除`主实例`节点。

## 前提条件

- 已获取 QingCloud 管理控制台登录账号和密码，且已获取集群操作权限。
- 已创建 PostgreSQL 集群，且集群状态为**活跃**。

## 操作步骤

1. 登录 QingCloud 管理控制台。
2. 选择**产品与服务** > **数据库与缓存** > **关系型数据库 PostgreSQL**，进入集群管理页面。
3. 选择目标集群，点击目标集群 ID，进入集群详情页面。
4. 在**节点**页签，勾选目标节点。
5. 点击**删除**，弹出节点删除确认窗口。

    <img src="../../../_images/delete_node.png" alt="删除节点" style="zoom:50%;" />

6. 确认配置信息无误后，点击**确认**，返回节点列表页面。

   待集群状态切换为**活跃**，即节点删除完毕。
