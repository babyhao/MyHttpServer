该项目实现了一个简易版的 httpserver 服务框架，项目结构如下所示：

MyHttpServer---|
               |---httpserver---|
               |                |---httpserver.py（主程序）
               |                |---setting.py（httpserver配置）
               |
               |---webframe---|
                              |---static（静态资源）
                              |---webframe.py（主程序）
                              |---setting.py（框架配置）
                              |---urls.py（存放路由）
                              |---views.py（应用处理程序）