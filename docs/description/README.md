---
title: 文档说明
---

本篇文档主要提供授权服务器的接口文档以及使用说明；叙述多个授权模式的使用流程等信息。

## 项目介绍

此项目为贵州民族大学的授权中心的授权服务器实现，基于标准的 [OAuth2](https://tools.ietf.org/html/rfc6749) 开放授权协议构建，作为授权服务器角色为资源服务器以及客户端提供功能实现。

## 授权模式

目前主要提供以下四种授权模式：

1. 授权码模式 —— 最为安全的授权模式
2. 密码模式 —— 最为简单的授权模式
3. 手机验证码模式
4. 邮箱验证码模式
