
# 欢迎使用yii2cms后台快速搭建框架

------

本框架基于YII2+Layui，后端主要集成了如下功能：
> * RBAC权限控制
> * 前台用户管理
> * 系统参数配置
> * 系统访问日志
> * 微信公众号开发组件


查看演示站点-账号：demo 密码：123456

yii2后台，喜欢就点个星

系统目录结构如下


```
api
    assets/             资源发布文件
    controllers/        控制器文件
    models/             模型文件
    modules/            模块文件
        v1/             接口V1
            controllers 控制器
            views       视图文件
            Module.php  模块
    runtime/            运行缓存
    views/              视图文件
    web/                入口目录
common
    config/             配置文件
    mail/               邮件模板
    models/             模型文件
    tests/              测试模块
console
    config/             配置文件
    controllers/        控制器文件
    migrations/         数据库迁移文件
    models/             模型文件
    runtime/            运行缓存
backend
    assets/             资源发布文件
    config/             配置文件
    controllers/        控制器文件
    models/             模型文件
    modules/            后台其他模块
    runtime/            运行缓存
    tests/              测试模块
    views/              视图
    web/                入口文件
frontend
    assets/             资源发布文件
    config/             配置文件
    controllers/        控制器文件
    models/             模型文件
    runtime/            运行缓存
    tests/              测试模块
    views/              视图
    web/                入口文件
    widgets/            插件
vendor/                 composer安装文件
environments/           环境文件
yii2_cms.sql            数据库文件
```

**安装教程**

 1. 使用本系统之前先安装composer工具
 2. 把本项目克隆下来 `git clone https://github.com/changchang700/yii2cms.git`
 3. 运行 `composer install`,然后再在项目根目录运行 `php init` 进行项目初始化配置
 4. 导入数据库文件，数据库文件在yii2cms下的yii2_cms.sql，直接到如即可






