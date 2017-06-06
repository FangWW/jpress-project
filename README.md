# JPress-project
## 新建jpress主题,自动适配PC端和移动端,管理后台增加smzdm(什么值得买)的爬虫功能,如图:
### [主题地址](https://github.com/FangWW/jpress-project/tree/master/jpress/jpress-web-template-ui3)
#### [Mobile端主页](#mobile端主页) 
#### [PC端主页](#pc端主页)
### #Mobile端主页
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～mobile.png "github")
### #文章类容
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/PEST、SWOT、五力模型、波士顿矩%20%20%20嘿～.png "github")
### #关于
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～mobile-about.png "github")

### #PC端主页
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/%E7%9B%98%E5%AD%90%E9%85%B1%20%20%20%E5%98%BF%EF%BD%9E.png "github")
### #文章
![github](https://github.com/FangWW/jpress-project/blob/master/jpress/2016%E5%B9%B4%20%E6%8E%A8%E8%8D%90%20%E6%9C%80%E5%85%A8%20%E9%9D%9E%E6%B7%B1%E6%88%B7%E5%BA%94%E5%B1%8A%E7%94%9F%20%E4%B8%AA%E4%BA%BA%E5%8A%9E%E7%90%86%E6%B7%B1%E6%88%B7%E6%B5%81%E7%A8%8B%20%20%20%E5%98%BF%EF%BD%9Earticle.png?raw=true "github")
### #登陆
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～login.png "github")
### #注册
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～reg.png "github")
### #用户中心
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～center.png "github")
### #搜索
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～search.png "github")
### #关于
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～about.png "github")
### #联系
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～contact.png "github")
### #404
![github](https://raw.githubusercontent.com/FangWW/jpress-project/master/jpress/盘子酱%20%20%20嘿～404.png "github")



### 以下是原作者
![](http://7xv9xp.com1.z0.glb.clouddn.com/1.png)

演示站点：[http://www.yangfuhai.com](http://www.yangfuhai.com)

JFinal和JPress视频教程：[http://www.yangfuhai.com/post/6.html](http://www.yangfuhai.com/post/6.html)

JPress模板制作视频教程：[http://www.yangfuhai.com/post/22.html](http://www.yangfuhai.com/post/22.html)

JPress官网：[http://jpress.io](http://jpress.io) 

JPress文档：[https://github.com/JpressProjects/jpress/blob/master/DOC.md](https://github.com/JpressProjects/jpress/blob/master/DOC.md) 


## 简介
JPress，一个wordpress的java代替版本，使用JFinal开发。支持类似wordpress的几乎所有功能，比如：模板，插件等。同时在模板上，JPress提出了“模板即模型”的概念，方便模板制作人灵活制作业务模型，移除了widget等繁杂功能，同时在模板和插件制作上比wordpress更加灵活简洁。

但是，JPress又不是wordpress的java版本，它天生融合了微信公众平台，整合了国内众多云平台、短信发送、邮件发送平台，独创的“模板即模型”概念是wordpress所不具备的，只有资深的wordpress玩家才能体会里面的微妙关系。同时后续会添加微信文章同步，QQ公众平台，今日头条，一点资讯等新媒体的文章同步功能，更加国产和本地化。

## 在功能方面
*  支持自定义模型，自定义模型通过模板来定义，而不是后台功能。同时模型内容支持自定义类别，比如文章模型支持专题、分类、标签等类别。
* 支持多模板引擎，默认使用Freemarker，模板制作者可以使用其他引擎比如thymeleaf来渲染，同时支持后台在线编辑模板（目前暂时只支持freemarker引擎）。
* 支持多数据库类型，可以配置不同的数据库（目前暂只支持mysql）。
* 支持多编辑器，后台可视化编辑和markdown编辑自由切换，默认支持在线图片编辑和代码高亮等功能。
* 支持插件化，几行代码就可以完成一个插件的开发，git.oschina.net和github上已经有插件的helloworld实例。
* 支持自定义URL，网站内容URL风格自定义。
* API支持，方便APP或其他第三方调用数据。
* 国际化支持，使用JPress轻松制作任何语言的网站。
* 极简的SEO功能，可以为每篇文章、每个分类、每个标签单独设置SEO，支持sitemap输出。
* 用户注册支持邮件和短信验证，目前短信服务商暂时只支持阿里大鱼。
* 支持CDN设置，包括七牛，阿里云，又拍云等。
* 上传图片支持水印设置，同时上传图片自动剪切成为模板需要的多种图片尺寸，保证图片显示不会拉伸。
* 用户登录支持第三方登录，支持QQ、微信、微博、开源中国、github、Facebook、twitter、linkedin（目前只完成QQ、微信、微博、开源中国、github的登陆）。



## 在微信方面

* 支持微信菜单设置。
* 支持自动回复，添加关键字和回复内容。
* 支持默认回复，包括：用户关注时、进入多客服时、退出多客服时、发送图片时、发送语音时、发送视频时、发送位置时、发送连接时、用户扫描了带参数的二维码时、用户摇一摇时。
* 所有的自动回复或默认回复支持“高级回复”功能，比如回复一篇文章，回复一个网址…高级回复是由JPress内置开发的特殊回复，但完全可配置，今后会增加更多的“高级回复”功能。
* 自动回复或默认回复支持插件回复，调用JPress插件完成回复。
* 支持文章搜索，回复关键字即可返回关键字匹配文章。
* 未来会支持文章同步或微信导入等实用功能。


## 在技术方面
* 自豪的采用了JFinal作为核心，JPress也是得益于JFinal灵活的架构。在JFinal framework开源体系里，JPress关心每行逻辑的实现，重视每行代码质量，应该属于JFinal的最佳实践，所以也应该是每个JFinaler必读的项目。
* 使用Freemarker和thymeleaf作为模板引擎。JPress内置的独创缓存，使得的UI渲染速度已经和模板引擎无关。
* 使用了tinymce做可视化编辑器，使用simplemde做markdown编辑器。两者可以后台自由切换。
* 文件和图片上传的UI插件使用了fine-uploader。
* 在前端上，JPress使用了jquery，bootstrap，admin lte，font-awesome，x-editable，fastclick，toastr，tag-editor，pace，layer等。
* 在安全方面，尽管我个人做了非常多的努力，已经在XSS，CSRF，SQL注入，Cookie安全等方面做了很多的工作，但是还是需要更多的人来一起挖掘和完善，安全是一个永恒的话题。（但是对于新手朋友来说，这些安全应该都是值得去学习和了解的，不是吗？）
* 支持分布式部署，JPress重写了HttpSession，使用ehcache实现了session的功能，同时在项目中大量依赖于cookie，在分布式架构上毫无压力。

## JPress有以下特点
#### 1、 轻。

>轻到只有 **8张** 数据表，却能实现wordpress的几乎所有功能。依赖的jar包也极度轻，目前只有cos-26Dec2008.jar、druid-1.0.16.jar、ehcache-2.7.5.jar、fastjson-1.2.7.jar、freemarker-2.3.23.jar、javax.mail.jar、jfinal-2.2-bin-with-src.jar、jfinal-weixin-1.7-bin-with-src.jar、jsoup-1.8.3.jar、log4j-1.2.17.jar、mysql-connector-java-5.1.36.jar、slf4j-api-1.7.7.jar、slf4j-log4j12-1.7.7.jar、jetty-server-8.1.8.jar 这 **14个** jar包，而且其中jetty-server-8.1.8.jar 不是必须的，只用于方便调试。<br /> 包括jar包在内的整个项目在20MB左右。

#### 2、 快。

>无论多么复杂的页面，JPress响应几乎在10毫秒内，同时JPress支持阿里云，七牛，又拍云等CDN作为加速，支持分布式部署等功能，就算是香港的服务器，只能用“飞快”来形容。

#### 3、灵活。

>JPress提出的“模板即模型”的概念，模板制作人可以用JPress来做博客，新闻系统，论坛，问答社区，商城…加上其灵活的插件功能，几乎可以用来做任何类型的网站。

#### 4、国产。

>因为国产，所以更符合国人需求。JPress天生融合了微信公众号，JPress内置了 阿里大鱼 的短信发送功能，支持了QQ邮箱，163邮箱等作为邮件发送服务器，后续会增加微信模板消息发送通知用户等更加符合国人需求的功能。


## 最最重要的的是
JPress使用了比wordpress更宽松的LGPL开源协议，同时和国内的那些采用了 **私有协议** （比如保留版权，保留连接等）的“开源”产品并不是一个级别的。

###最后来几张截图
![](http://7xv9xp.com1.z0.glb.clouddn.com/1.png)
![](http://7xv9xp.com1.z0.glb.clouddn.com/2.png)
![](http://7xv9xp.com1.z0.glb.clouddn.com/3.png)
![](http://7xv9xp.com1.z0.glb.clouddn.com/4.png)
![](http://7xv9xp.com1.z0.glb.clouddn.com/5.png)
备注：第二套模板（the3）还不完善，如果要做网站请使用第一套模板 或者 自行设计一套模板。

### 目前我在 [全职] 开发JPress，如果您觉得这个产品对您有用，您可以捐助下我，让我有理由继续下去，非常感谢。
![](http://7xv9xp.com1.z0.glb.clouddn.com/zz.jpg)


#### 现在微信捐助无法得知捐助人昵称，欢迎添加我的个人微信:wx198819880
### 非常感谢以下朋友的捐助：

| 名字      | 金额   | 方式  | 说明  | 时间  |
| :-------: |:----: | :-----:|----- |-----|
| 微信匿名  | ￥15.00  | 微信   | 无 | 2016-9-19 17:33|
| 微信匿名  | ￥6.66  | 微信   | 无 | 2016-9-19 16:43|
| 信仰释心  | ￥99.99  | 支付宝   | 加油！ | 2016-9-8 21:50|
| billy  | ￥66.00  | 支付宝   | 希望jpress越做越好！ | 2016-9-8 10:28|
| 蔚蓝一方  | ￥200.00  | 支付宝   | 感谢你共享的jpress，加油！ | 2016-8-31 19:16|
| 幸福乐呵呵  | ￥50.00  | 支付宝   | 希望能上架插件功能，帮主，顶你 | 2016-8-27 19:33|
| 美男子  | ￥20.00  | 支付宝   | 还没有用，精神可嘉，钱不多表示支持 | 2016-8-25 15:24|
| 匿名  | ￥16.88  | 微信匿名   | 无 | 2016-8-23 16:31|
| 西瓜  | ￥18.00  | 支付宝   | 学习jFinal发现了jpress加油。 | 2016-8-23 17:14|
| 刘磊  | ￥50.00  | 微信红包   | 请继续坚持，加油！ | 2016-8-22 19:52|
| 执子之手  | ￥6.66  | 微信红包   | 钱少人傻，不要介意 | 2016-8-21 10:11|
| 文杰  | ￥20.00  | 支付宝   | 支持下，海哥加油 | 2016-8-21 10:11|
| 網oo魈oo卛  | ￥9.00  | QQ红包   | 无 | 2016-8-16 17:41|
| 匿名  | ￥10.00  | 微信捐助   | 无 | 2016-8-12 11:19|
| dythzx  | ￥100.00  | 微信红包   | 希望Jpress越做越好，已经采用做公司的网站了 | 2016-8-12 09:44|
| skyearth  | ￥2.00  | QQ红包   | 无 | 2016-8-10 23:40|
| 匿名  | ￥10.00  | 微信捐助   | 无 | 2016-8-9 21:22|
| Crazy Guy  | ￥10.00  | QQ红包   | 无 | 2016-8-7 18:31|
| Dee  | ￥99.00  | 微信红包   | 无 | 2016-8-4 23:56|
| 匿名  | ￥25.00  | 微信捐助   | 无 | 2016-8-4 09:14|
| 匿名  | ￥10.00  | 微信捐助   | 无 | 2016-8-3 14:41|
| 聪亮  | ￥18.00  | 微信红包   | 支持一下jpress，加油！ | 2016-8-2 13:37|
| 程 | ￥100  | 支付宝   | 无 | 2016-8-1 16:42|
| 吴益峰 | ￥100  | 微信捐助   | 无 | 2016-8-1 16:40|
| 匿名  | ￥18.00  | 微信捐助   | 无 | 2016-7-30 22:46|
| 松 | ￥99.99  | 支付宝   | 捐助有价，开源精神无价 | 2016-7-28 16:20|
| 米松 | ￥28.88  | 支付宝   | 支持一下 | 2016-7-28 15:28|
| 张富生  | ￥10.00  | 微信红包   | 希望jpress越做越专业 | 2016-7-23 18:37|
| 来点银子吧  | ￥10.00  | 支付宝   | java就应该有这个项目，坚持，加油！ | 2016-7-23 21:00|
| 匿名  | ￥9.99  | 微信捐助   | 无 | 2016-7-23 18:37|
| 昊  | ￥8.00  | 支付宝   | 加油加油 | 2016-7-21 14:40|
| 匿名  | ￥6.66  | 微信捐助   | 无 | 2016-7-21 10:58|
| 浒  | ￥1.00  | 支付宝   | 加油 | 2016-7-19 08:06|
| 指尖沙向  | ￥9.90  | 微信捐助   | 无 | 2016-7-18 15:07|
| 落落的月(wtf)  | ￥2.00  | 微信捐助   | 无 | 2016-7-18 11:58|
| Cennac     | ￥1.50  | 微信捐助   | 无 | 2016-7-12 08:09|
| jungle     | ￥6.66  | 支付宝   | 加油 | 2016-7-11 16:54|
| 浒     | ￥10.00  | 支付宝   | 加油 | 2016-7-11 14:04|
| 十里     | ￥66.66  | 微信捐助   | 无 | 2016-7-10 23:23|
| 甘叶川     | ￥88.80  | 支付宝   | 支持一下 | 2016-7-9 16:49|
| Mr.Kn   | ￥9.90  | 微信捐助   | 无 | 2016-7-7 10:16|
| 小李     | ￥6.66  | 支付宝   | 加油| 2016-7-5 11:09|
| 仔仔     | ￥6.66  | 支付宝   | 支持JPress | 2016-7-5 11:06|
| beyonds     | ￥6.66  | 支付宝   | 开源的路上，加油 | 2016-7-2 10:38|
| L RO Xin     | ￥6.66  | 微信捐助   | 无 | 2016-7-1 22:35|
| 一棵树     | ￥6.66  | 支付宝   | 转账 | 2016-7-1 17:17|
| 倡萌     | ￥100.00  | 支付宝   | 希望坚持到底，不要虎头蛇尾 | 2016-7-1 12:14|
| 曾     | ￥20.00  | 支付宝   | z201 没玩过jfinal，来观摩下。 | 2016-6-30 22:43|
| 一诺雨     | ￥6.60  | 微信捐助   | 无 | 2016-6-29 18:17|
| 射手座     | ￥30.00  | 微信捐助   | 无 | 2016-6-28 13:21|
| Jack     | ￥6.66  | 微信捐助   | 无 | 2016-6-24 22:04|
| 刘亮     | ￥88.00  | 微信捐助   | 无 | 2016-6-24 13:18|
| 取名字真的很烦     | ￥20.00  | 微信捐助   | 无 | 2016-6-24 00:02|
| L❤️L     | ￥28.00  | 微信捐助   | 无 | 2016-6-22 17:37|
| 守望者     | ￥20.00  | 微信捐助   | 无 | 2016-6-22 15:56|
| 天V梦     | ￥10.24  | 微信捐助   | 无 | 2016-6-22 10:52|
| 叫我大王     | ￥20.00  | 支付宝   | 简单支持下，加油 | 2016-6-21 15:00|
| 麋鹿     | ￥8.88  | 微信捐助   | 无 | 2016-6-21 11:53|
| DNS     | ￥9.99  | 支付宝   | 越做越好，开始学习jpress | 2016-6-19 20:18|
| 杨子锋     | ￥18.88  | 支付宝   | 支持，学习 | 2016-6-19 12:23|
| 帅轻     | ￥18.88  | 支付宝   | 为信仰充值 | 2016-6-19 10:32|
| Macaque     | ￥20.00  | 微信捐助   | 无 | 2016-6-18 23:02|
| 正灵     | ￥1.00  | 支付宝   | 对jpress支持下 | 2016-6-18 21:42|
| 黄志清     | ￥18.88  | 微信捐助   | 无 | 2016-6-17 18:48|
| 啊春       | ￥18.88  | 微信捐助   | 无 | 2016-6-17 12:44|
| 万利       | ￥6.66  | 微信捐助   | 无 | 2016-6-17 11:17|
| 做个好农民  | ￥28.88  | 微信捐助   | 无 | 2016-6-16 14:41|
| 五v熊      | ￥20.00 | 支付宝捐助  | 有beetl版的就更好了 | 2016-6-16 14:34|
| 明    		| ￥10.00  | 微信捐助   | 无 | 2016-6-16 13:46|
| 蔡菜      | ￥2.00 | 支付宝捐助  | 加油，快点完成，等着用呢 | 2016-6-16 11:23|
| Mr.goku    | ￥9.90  | 微信捐助   | 无 | 2016-6-16 10:25|
| 张腾飞    | ￥20.00 | 微信捐助   | 无 | 2016-6-15 16:04|
| 浮云      | ￥10.24 | 支付宝捐助  | 支持这样的好项目！ | 2016-6-15 14:49|
| 兴伟      | ￥20.00 | 支付宝捐助  | 好项目，支持！ | 2016-6-15 11:38|
| jk(0ZEO-ZHH)   | ￥9.90  | 微信捐助   | 无 | 2016-6-15 11:10|
| Aguang    | ￥19.99  | 微信捐助   | 无 | 2016-6-14 20:23|
| 雷电      | ￥7.00  | 微信捐助   | 无 | 2016-6-14 20:22|
| 漠然      | ￥20.00 | 支付宝捐助  | JPress -mrtid | 2016-6-14 12:34|
| 雷师奶     | ￥16.88 | 支付宝捐助  | 支持 | 2016-6-14 11:57|
| 野渔      | ￥13.14  | 微信捐助   | 无 | 2016-6-14 09:49|
| cknote    | ￥6.66  | 微信捐助   | 无 | 2016-6-14 09:10|
| 我(enj***@gmail.com) | ￥30.00  | 支付宝捐助   | 祝jpress越来越好！ | 2016-6-13 19:03|
| 勐萌      | ￥6.66  | 微信捐助   | 无 | 2016-6-13 18:01|
| 盛宇伟    | ￥2.00  | 微信捐助   | 无 | 2016-6-13 15:41|
| Dean     | ￥10.00 | 支付宝捐助  | 简单支持下 | 2016-6-13 12:53|
| 花无雨    | ￥20.00 | 微信捐助   | 无 | 2016-6-13 11:23|
| 灿灿宝宝  | ￥18.88  | 支付宝捐助 | 要养老婆孩纸，没财权，支持jpess下 | 2016-6-13 11:01|



### 您也可以加入JPress交流QQ群：288397536 ，欢迎给我提建议和bug。<br >或者给我邮件：fuhai999@gmail.com 


####0.3版本较之前的版本，数据字段更新如下：

```
content表：
新增：
 +  `summary` text COMMENT '摘要',
 +  `link_to` varchar(256) DEFAULT NULL COMMENT '连接到(常用于谋文章只是一个连接)',
 +  `markdown_enable` tinyint(1) DEFAULT '0' COMMENT '是否启用markdown',
 +  `author` varchar(128) DEFAULT NULL COMMENT '匿名稿的用户',
 +  `user_email` varchar(128) DEFAULT NULL COMMENT '匿名稿的邮箱',
 +  `user_ip` varchar(128) DEFAULT NULL COMMENT 'IP地址',
 +  `user_agent` text COMMENT '发布浏览agent',
 +  `rate` int(11) DEFAULT NULL COMMENT '评分分数',
 +  `rate_count` int(10) unsigned DEFAULT '0' COMMENT '评分次数',
 +  `comment_time` datetime DEFAULT NULL COMMENT '最后评论时间',



user表：
新增：
 +  `realname` varchar(128) DEFAULT NULL COMMENT '实名',
 +  `email_status` varchar(32) DEFAULT NULL COMMENT '邮箱状态（是否认证等）',
 +  `mobile` varchar(32) DEFAULT NULL COMMENT '手机电话',
 +  `mobile_status` varchar(32) DEFAULT NULL COMMENT '手机状态（是否认证等）',
 +  `telephone` varchar(32) DEFAULT NULL COMMENT '固定电话',
 +  `facebook` varchar(256) DEFAULT NULL,
 +  `linkedin` varchar(256) DEFAULT NULL,
 +  `birthday` datetime DEFAULT NULL COMMENT '生日',
 +  `company` varchar(256) DEFAULT NULL COMMENT '公司',
 +  `occupation` varchar(256) DEFAULT NULL COMMENT '职位、职业',
 +  `address` varchar(256) DEFAULT NULL COMMENT '地址',
 +  `zipcode` varchar(128) DEFAULT NULL COMMENT '邮政编码',
 +  `site` varchar(256) DEFAULT NULL COMMENT '个人网址',
 +  `graduateschool` varchar(256) DEFAULT NULL COMMENT '毕业学校',
 +  `education` varchar(256) DEFAULT NULL COMMENT '学历',
 +  `idcardtype` varchar(128) DEFAULT NULL COMMENT '证件类型：身份证 护照 军官证等',
 +  `idcard` varchar(128) DEFAULT NULL COMMENT '证件号码',


修改：
-  `weibo` varchar(64) DEFAULT NULL COMMENT '微博',
+  `weibo` varchar(256) DEFAULT NULL COMMENT '微博',

-  `phone` varchar(32) DEFAULT NULL COMMENT '手机电话',
+  `mobile` varchar(32) DEFAULT NULL COMMENT '手机电话',


```
