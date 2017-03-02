# ci_guestbook
> 首次书写✍️ 2017/02/28


<br/>
<br/>

CI框架实战项目之简易留言本2：入门CI框架的基本操作，熟悉类库的使用、辅助函数的使用、数据库操作，以及配置文件的管理

<br/>

## 1 在线视频
http://u8code.org


<br/>
## 2 其中 dev_log 目录是 开发目录
+ 留言本测试数据.sql  数据库文件
+ guest静态页面2.zip 留言本静态页面





<br/>


## 3 前台模板： 留言本
> 可以参考下，未使用CI框架实现的 建议留言本项目的功能：

> 下载地址： https://github.com/mrlindaxue/guestbook-2

> 目前 留言本前台模板 已经整理放在 dev_log/guestbook_static

<br/>

+ 包括了一下几个界面
	+ 留言首页（列表） index.html
	+ 发布留言 add.html
	+ 编辑留言 update.html
	+ 删除留言（无视图页面） 

<br/>
<br/>

## 4 后台模板
> 参考地址： https://github.com/mrlindaxue/hia_admin 	

> 目前 后台模板 已经整理放在 dev_log/admin_static



+ 管理员的管理
	+ 列表 admin/index.html
	+ 添加 admin/add.html
	+ 编辑 admin/update.html
	+ 删除 


+ 留言的管理
	+ 列表 guestbook/index.html
	+ 详情 guestbook/show.html
	+ 删除 


+ 登录与退出


<br/>
<br/>

## 5 CI 框架
> 参考地址： http://codeigniter.org.cn/user_guide/index.html

> CI项目代码 放在 web目录


====

以下是CI的常用内容的链接

+ 常规主题
	+ URL处理 ： http://codeigniter.org.cn/user_guide/general/urls.html
	+ 控制器： http://codeigniter.org.cn/user_guide/general/controllers.html
	+ 视图： http://codeigniter.org.cn/user_guide/general/views.html
	+ 模型： http://codeigniter.org.cn/user_guide/general/models.html
	+ 路由： http://codeigniter.org.cn/user_guide/general/routing.html


+ 类库参考
	+ 输入类：http://codeigniter.org.cn/user_guide/libraries/input.html
	+ session类：http://codeigniter.org.cn/user_guide/libraries/sessions.html
	+ URI类：http://codeigniter.org.cn/user_guide/libraries/uri.html
	+ 分页类： http://codeigniter.org.cn/user_guide/libraries/pagination.html


+ 辅助函数
	+ 验证码： http://codeigniter.org.cn/user_guide/helpers/captcha_helper.html
	+ 字符串： http://codeigniter.org.cn/user_guide/helpers/string_helper.html
	+ URL：http://codeigniter.org.cn/user_guide/helpers/url_helper.html


+ 数据库
	+ 数据库配置： http://codeigniter.org.cn/user_guide/database/configuration.html
	+ 数据库连接： http://codeigniter.org.cn/user_guide/database/connecting.html
	+ 查询构造器： http://codeigniter.org.cn/user_guide/database/query_builder.html
	+ 生成查询结果：http://codeigniter.org.cn/user_guide/database/results.html
	+ 查询辅助函数： http://codeigniter.org.cn/user_guide/database/helpers.html





