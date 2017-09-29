### SpringCloud经典架构


![输入图片说明](https://github.com/qccr-twl2123/springcloud/blob/master/images/springcloud架构.png "在这里输入图片标题")

#### 权限治理,我们需要解决哪些问题?
```
1.安全校验(决定我们是否可以访问资源):Session,JWT,Security,OAuth
2.权限校验(决定我们可以访问哪些资源):JWT和Security整合使用 
3.XSS跨站攻击解决方案
4.跨域访问解决方案,代码层Cors配置,nginx配置.
5.https配置方案
```

#### 服务治理篇,我们经常在解决哪些领域的问题? 
```
1.参数校验框架(Hibernate Validator)
2.事务的一致性(强一致性,弱一致性)
3.线程安全
4.消息系统
5.服务的降级处理
6.缓存问题:AutoLoadCache
7.分页框架:PageHelper
8.集中式日志管理:mongodb 存储日志and查询
9.加密and解密: MD5,RSA2
10.任务调度框架quartz运用
```

#### 经典系统架构
```
1.秒杀系统架构方案
2.红包优惠券系统架构
3.商品体系架构方案(SKU,SPU)
4.时间段折扣优惠系统(电影售票系统:按星期,按时间段进行优惠策略设计)
5.还款计划架构(p2p平台借款端)

```

#### 数据库篇
```
1.分布式ID生成机制
2.索引的运用
```

#### 运维治理
```
1.排查线上问题:从日志角度排查,从系统角度排查
2.JVM调优
3.springboot线上部属脚本
 
```

#### 实战思维训练
```
找到离问题最近的影响点
```



