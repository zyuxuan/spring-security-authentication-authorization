# Spring Security技术栈开发企业级的认证和授权的项目

## 运用的技术：

Spring Security、Spring Social、Spring Security OAuth

## 特点：

支持集群环境，跨应用工作，SESSION控制，控制用户权限，防护与身份认证相关的攻击

主要有3种认证方式（同时支持浏览器和APP等多种前端渠道）：

①用户名+密码认证	②手机号+短信认证	③第三方认证（QQ、微信等）

## 代码结构：

zyuxuan-security：主模块

zyuxuan-security-core：核心业务逻辑

zyuxuan-security-browser：浏览器安全特定代码

zyuxuan-security-app：app相关特定代码

zyuxuan-security-demo：样例程序
