## 环境要求（Requirements）

- **PHP : 5.6**
- **Laravel : 5.1.***
- **Composer**

## 我的开发环境（My Development Environment）

- Homebrew
- PHP - 7.0.7
- Redis - 3.2.0
- Nginx - 1.10.1
- MySQL - 5.7.13

## 安装步骤（Installation）

1. **`git clone https://github.com/luisedware/CowCat.git`**
1. **`cd CowCat`**
1. **`sudo chmod -R 777 storage/`**
1. **`sudo composer install`**
1. **`sudo npm install`**
1. **`sudo vi .env`**
1. **`gulp`**
1. **`php artisan migrate:refresh --seed`**
1. **`php artisan serve`**
1. **`gulp watch`**

> 默认账号: user@qq.com / admin@qq.com 密码: 123456

## 计划新增功能（Todo）

- [x] 首页展示（Home Page）-- 初步实现,等待完善细节
- [x] 发送邮件（Send Email）-- 初步实现,等待重构
- [ ] 在线支付（Online Payment）
- [x] 文件上传（File Upload）-- 初步实现,等待重构
- [ ] OAuth2.0 注册与登录（Register & Login By OAuth2.0）
- [ ] 富文本编辑器和 Markdown 编辑器（Rich Text Editor && Markdown）


## 感谢（Thanks）

- Site
	- [PHPHub](https://phphub.org/)
	- [LaraBase](http://laravelbase.com/)
	- [Laravel.So](http://laravel.so/)
	- [Laravel 学院](http://laravelacademy.org/)
- Project
	- [BootstrapCMS/CMS](https://github.com/BootstrapCMS/CMS)
	- [yccphp/laravel-5-blog](https://github.com/yccphp/laravel-5-blog)
	- [yuansir/laravel5-rbac-example](https://github.com/yuansir/laravel5-rbac-example)
	- [rappasoft/laravel-5-boilerplate](https://github.com/rappasoft/laravel-5-boilerplate)
- PHP Package
	- [zizaco/entrust](https://github.com/Zizaco/entrust)
	- [orangehill/iseed](https://github.com/orangehill/iseed)
	- [arcanedev/log-viewer](https://packagist.org/packages/arcanedev/log-viewer)
	- [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar)
	- [barryvdh/laravel-ide-helper](https://github.com/barryvdh/laravel-ide-helper)
- Javascript Package
	- [ztree](https://github.com/uibox/ztree)
	- [admin-lte](http://github.com/almasaeed2010/AdminLTE)
	- [sweetalert](https://github.com/t4t5/sweetalert)
