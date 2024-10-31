=== 七牛云存储插件 ===
Contributors:  verylove
Donate link: http://www.75271.com/
Tags: qiniu, tuchuang , 七牛 , 七牛云 , 云存储，图床
Requires at least: 3.0.0
Tested up to: 4.9.2
Stable tag: 4.9.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html


== Description ==

#七牛云存储插件

该插件让你直接在编辑器页面上传图片到七牛对象存储空间
上传完成后自动在编辑器中添加图片，不需要设置全站CDN
功能简单，更方便


#介绍

#详细介绍：
 [http://www.75271.com/2954.html](http://www.75271.com/2954.html)

#安装

1. 上传 `qiniu-cloudtuchaung`目录 到 `/wp-content/plugins/` 目录
2. 在后台插件菜单激活该插件
3. 在后台设置设置accesskey,screctkey,bucket,七牛绑定域名
4. 后台配置附件访问域名可使用单独域名访问附件

== Screenshots == 

1. 七牛镜像存储设置
![](https://ps.w.org/qiniu-cloudtuchuang/assets/screenshot-1.png?rev=1647131)

2.编辑器
![](https://ps.w.org/qiniu-cloudtuchuang/assets/screenshot-2.png?rev=1647155)

3.后台设置
![](https://ps.w.org/qiniu-cloudtuchuang/assets/screenshot-3.png?rev=1647155)

== Changelog ==
2018-1-23
增加独立附件访问功能

2018-1-12
修复上传图片按钮BUG

2017-2-26

更新自动同步七牛云路径BUG

2017-2-25
初始版本

== Frequently Asked Questions ==

###为什么不能上传图片的同时同步上传到七牛云？
>后台 设置->七牛云图床->是否同步上传,勾选选项


###图片怎么能自动把图片同步七牛云存储时同步路径一起?
>后台 设置->七牛云存储->前缀 ,修改为空即可

###不能上传？

>上传前要设置accessKey和SecretKey还有bucket
不要有多余的 “/”或空格 哦

####自动添加的图片title,alt信息？

>信息默认为文章标题，如果标题为空则为空

###为什么我上传的图片不显示？

>请确定编辑器是在可视化下，文本模式不能正常添加链接

###可以上传那些附件内容？

>插件没有限制附件的类型

###附件怎么使用我自己的域名访问？

>到系统的设置-》常规-》附件访问域名，填写附加域名。


== Upgrade Notice == 

>更新最新七牛接口SDK 