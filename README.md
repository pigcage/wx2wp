# wx2wp
微信文章转发到wordpress

在前端页面wxposter.html中填写信息，php后台将自动爬取链接中的微信文章内容，转发到wordpress博客，并将文中的图片进行本地化处理。后台处理为纯php实现。
本项目用于广东工业大学合唱团官网的文章发布，使用者可按需修改。

一些TODO：
1、图片本地化暂时不支持绑定对应文章id
2、背景图片的本地化功能暂时还没做
3、视频url参数获取函数还有一个内部的小bug
