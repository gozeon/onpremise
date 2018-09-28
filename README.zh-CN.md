# article

- http://www.yunweipai.com/archives/22303.html
- http://niexiaotao.cn/2018/08/18/从源码分析sentry的错误信息收集/
- https://www.jianshu.com/p/66e00077fac3
- https://www.jianshu.com/p/cea2d22fbb32


# 备注

1. 邮件服务器。默认使用`tianon/exim4`，这是个简单的邮件服务器，但是使用自己SMTP时会出现各种问题，解决办法是替换成`namshi/smtp`。
2. 数据映射。数据映射如果不成功，建议使用`docker inspect <>`， 查看`mount`的位置，进行迁移等其他操作。
