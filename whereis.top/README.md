
这个项目是我的“在哪”语音应用的webhook服务平台，已经部署了两个实例，中国实例对接了京东alpha，天猫精灵，小米小爱，百度bot；美国实例对接了alexa，Google正在调试中。

我将逐步的此项目中提交代码和说明文档，并对代码进行重构，最终迁移到一个新项目，作为语音应用开发框架。

项目特点：
  1. 整体解决方案，基于django二次开发，利用django的成熟部署方案，可以迅速上线。可采用wscgi+nginx方式运行，https由nginx解决
  2. 面向开发过程的调试支持，使用django自带orm框架，简单快速的实现了数据库日志；
  3. 测试方案及代码

目前项目对京东alpha平台的开发者是可用的，需要开发者自己查询django使用文档，服务器部署可用使用uwsgi+nginx方案，配置nginx实现https服务



