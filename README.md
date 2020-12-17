
<h2 align="center">
 enterprise-cms （开发中，暂时请勿线上使用，只供学习）
</h2>
<p align="center">
基于laravel6+laravel-admin2.0开发的办公用品管理系统，适用于中小型企业，项目内有查询快递功能，方便用户知道购买的办公用品的具体信息。新增导出excel功能方便公司对数据进行管理
</p>


[![GitHub issues](https://img.shields.io/github/issues/WXiangQian/enterprise-cms)](https://github.com/WXiangQian/enterprise-cms/issues)
[![GitHub stars](https://img.shields.io/github/stars/WXiangQian/enterprise-cms.svg?style=social&label=Star&maxAge=2592000)](https://github.com/WXiangQian/enterprise-cms/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/WXiangQian/enterprise-cms.svg?style=social&label=fork&maxAge=2592000)](https://github.com/WXiangQian/enterprise-cms/network/members/)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)


```
本项目可以直接用，也可以用于二次开发，二次开发具体看相关文档
laravel版本为6.*、laravel-admin版本为2.0.*
```
[laravel-admin2.0文档地址](https://laravel-admin.org/docs/zh/2.x)

### 克隆仓库
```
git clone git@github.com:WXiangQian/enterprise-cms.git
```

### 运行环境
```
"php": ">= 7.2.5"
```

### 生成配置文件
```
cp .env.example .env
```
你可以根据情况修改 .env 文件里的内容，如数据库连接、缓存、邮件设置等。

### 生成秘钥
```
php artisan key:generate
```

### 配置好.env以后执行以下命令进行创建数据库
(提示directory already exists 可忽略)

```
php artisan admin:install
```

### 如需测试数据，则执行以下命令填充数据库数据

```
php artisan db:seed
```

### 生成网站链接
```
php artisan serve

Laravel development server started: <http://127.0.0.1:8000>
http://127.0.0.1:8000为该网站的临时地址
```

### 后台

描述 | 详情
--- |---
后台登录地址 | http://127.0.0.1:8000/admin/auth/login
账号 | admin
密码 | admin
菜单管理地址 | http://127.0.0.1:8000/admin/auth/menu
### 头像问题
```
在.env中配置APP_URL=
配置好属于自己的域名，然后修改头像就可以看到真实路径了
```
**==================================后台截图==================================**

暂无


#### 如何贡献
所有合理的改动、优化、修正，新的组件，或者文档的修正、更新 相关的提交都会被接收
