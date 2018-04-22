## JBlog
-## 练手项目，基于Springmvc+MyBatis+Spring+Html+Freemaker+EasyUI+Mysql的个人博客系统
-## 介绍：
>1. 使用Maven3+Spring4+Springmvc+Mybatis3架构；数据库使用Mysql，数据库连接池使用阿里巴巴的Druid；
    页面使用FreeMaker模板引擎。
>2. 博客前台的头部及侧边栏的数据使用quartz按时间间隔去跑数据，并把存储于ServletContext，
   可以通过后台管理系统手动刷新数据，评论博客需要填写验证码，使用了kaptcha，并使用lucene实现了站内搜索功能。
>3. 使用EasyUI实现后台对博客、博客类别、用户评论、博主信息的管理；使用shiro实现登陆验证跟登陆后才能使用后台进行管理
    使用UEditor编辑博客,修改了UEditor的源码，支持配置文件上传路径。
