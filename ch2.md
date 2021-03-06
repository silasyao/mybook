# 第2章 概述

## 2.1 开发意图

开发本系统的本质意图是，解决当前食品安全生产过程的透明度和可追溯性。用户（消费者）通过手机访问平台，随时获取蔬菜种植生产的状态，包括水、土、投入品和作物的生长状况，生产人员在田间地头的工作情况，以此来建立信任，提高客户的黏性。

## 2.2 假设和约束

一块地种植服务平台的有效运行受以下条件约束：  
对于用户的假定，有一部能上网的智能手机（安卓、iPhone\)，能流畅使用，并且曾用手机进行网购（有京东APP、淘宝APP的购物经验）、安装了微信通讯工具且使用聊天、分享、发红包、支付、转账等功能。

## 2.3 运行环境

客户（消费者）的操作将使用智能手机（安卓平台、IOS平台）的自带浏览器或微信内置浏览器完成。根据操作系统的版本不同，其chrome及safari内核会稍有不同，  
平台运营及维护人员、业务人员、生产人员使用windows系统桌面浏览器，确保一种主流浏览器能正常使用平台业务即可，不用考虑IE浏览器的兼容问题。  
农技人员或外勤人员有移动办公需求的，其支行环境需求要兼职以上两种（手机移动端，和PC端）。

## 2.4 产品描述

_概括描述软件体系结构、软件组织结构、各子系统的主要功能等。_

## 2.5 设计和实现的约束条件

1. 系统运行在linux上； 
2. 数据库采用mysql引擎； 
3. 采用前后端分离技术实现页面展现； 
4. 后台采用php语言，建议使用laravel框架； 
5. 前端遵照HTML5标准、CSS3、ES2015标准，建议采用dcloud的MUI前端框架+VUEjs；


