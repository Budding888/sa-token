# [记住我]模式
--- 

如下图所示，一般网站的登录界面都会有一个 [ 记住我 ] 按钮，当你勾选它后，即时你关闭浏览器再次打开网站，也依然会处于登录状态，无须重复验证密码

![../static/login-view.png](../static/login-view.png)

那么在sa-token中，如何做到 [ 记住我 ] 功能呢？


### 在sa-token中实现记住我功能

sa-token的登录授权，默认就是`记住我`模式，为了实现`非记住我`模式, 你需要做一些适配

要




