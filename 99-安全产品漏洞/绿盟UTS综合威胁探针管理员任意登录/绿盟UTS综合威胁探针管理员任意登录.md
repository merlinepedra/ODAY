# 绿盟UTS综合威胁探针管理员任意登录

> 绿盟全流量威胁分析解决方案针对原始流量进行采集和监控，对流量信息进行深度还原、存储、查询和分析

## 影响版本
设备版本 <=V2.0R00F02SP02

## 漏洞利用
1.登录页面输入任意用户名密码
![](images/f17fc7e8.png)

2. 修改相应包为 `true`

![](images/aab102ec.png)

3. 返回重新登录，替换原来的`password`

![](images/1432414.png)
4. 登录成功

![](images/success.png)