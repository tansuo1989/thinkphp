## 修改说明：

* 修复原配置中的SESSION_EXPIRE在session()函数中无效的问题
* 分页类作了些修改，以适应bootstrap UI的分页样式
* verify类添加了draw方法，方便控制验证码的生成
* session 添加 服务端有效时间配置SESSION_EXPIRE,session对应cookie的有效期统一设置为浏览器的默认时间 ( session()函数中修改 )

## 2019.6.21 更新：
1. Modal 类中完善了忽略字段大小写的代码
2. Modal 缓存中的默认key 在原有的 sql语句的基本上添加了config ，保证切换数据库的时候能正确地读写缓存


## TODO
1. 完善使用默认模块时路由的bug

## <a href="https://github.com/top-think/thinkphp" target="_blank">原thinkphp 框架的简介 </a>
