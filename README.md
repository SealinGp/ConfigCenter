## ConfigCenter
```
#http://配置中心地址/匹配规则path

#匹配规则path:
#/{label}/{application}-{profile}.yml
#/{application}/{profile}[/{label}]
#/{application}-{profile}.yml
#/{application}-{profile}.properties
#/{label}/{application}-{profile}.properties

#从对应服务的配置中心读取相应的配置
#label       : git分支 master|...
#profile     : 配置文件版本 dev|pro|test...
#application : 应用名称,服务名称
#configType  : 配置文件的类型(后缀名)

```
分布式 config 配置仓库
