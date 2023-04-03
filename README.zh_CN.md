<a href="https://plugins.jetbrains.com/plugin/14723-restkit">![bg](doc/en/images/bg2.png)</a>

## 一套功能强大的 Restful 服务开发辅助工具集


[英文](./README.md) | [Github](https://github.com/newhoo/RESTKit) | [Gitee](https://gitee.com/newhoo/RESTKit) | [Jetbrains](https://plugins.jetbrains.com/plugin/14723-restkit/reviews)

**RestfulBox**插件致力于提升开发效率，只有实用常用的功能。源于最初版本的RestfulToolkit，同时融入了Postman的常用功能，丰富且完善的功能能极大地提高了Idea开发的效率。曾用名：RESTKit。

## 特性 ([3.0升级指南](doc/zh_CN/快速入门/3.0升级指南.md))
- 支持更多的jetbrains产品，不仅仅是idea
- Restful服务自动扫描、展示、跳转和导入导出
  - 原生Search Everywhere支持restful URL搜索 (<kbd>Ctrl \\</kbd> or <kbd>Ctrl Alt N</kbd>)
  - 窗口显示多层级 Services tree
  - URL和Method相互跳转
- 强大好用的请求工具：
  - 自定义参数格式，支持占位符变量，JSON自动格式化
  - 环境变量：支持变量使用、管理及迁移，提供内置函数和脚本函数
  - 全局请求头：支持和环境变量一起使用，提供内置函数和脚本函数
  - 参数库：支持Headers、Params、Body参数展示、保存和删除
  - 多协议：默认支持http，可扩展支持dubbo、grpc等
  - 请求脚本：支持前置/后置请求脚本
  - 请求响应的信息（HTTP报文）展示
  - 支持自定义数据源，实现API同步
  - 跨项目跨IDE浏览接口
- 日志保存：支持保存多协议服务的请求日志，比如HTTP报文格式
- 插件扩展：提供多个扩展点，便于自定义需求的实现
- 语言和框架：
  - 默认支持本地API文件和Sqlite存储
  - idea默认支持 Spring 体系 (Spring MVC with Java or Kotlin)

## 生态
通过公开的扩展点，可以轻松实现一些自定义需求，具体参考生态章节。当前已支持：
- [x] Spring MVC：默认支持，支持Java and Kotlin实现
- [x] Jax-Rs：通过插件支持，见 RESTKit-JAX-RS
- [x] Dubbo：通过插件支持，见 RESTKit-Dubbo ，支持扫描和请求发送
- [x] Redis：通过插件支持，见 RESTKit-Redis ，支持存储API到redis和简单的redis命令发送
- [x] Local Store：默认支持，支持存储API到本地文件
- [x] Sqlite数据源：默认支持，支持存储插件的所有数据到数据库

## 使用文档
- [中文文档-Github](doc/zh_CN/目录.md)
- [中文文档-语雀](https://www.yuque.com/newhoo/restkit)
- [Document-Github](doc/en/README.md)
- [CHANGELOG](doc/CHANGELOG.md)

## 联系 & 反馈
如果你觉得本插件不错，请赏个好评吧，同时也欢迎提供宝贵的建议。🌟 Star

[Issues](https://github.com/newhoo/RESTKit/issues) | [Email](mailto:huzunrong@foxmail.com) | [Jetbrains评分](https://plugins.jetbrains.com/plugin/14723-restkit/reviews)

> 注意  
> 反馈时请务必附上必要信息：Idea版本、插件版本、异常内容、复现方式(如果有)、诉求等。


## 支持作者
你的支持是鼓励我前行的动力，非常感谢~

![pay](doc/en/images/pay.png)