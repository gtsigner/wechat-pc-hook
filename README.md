## 删除项目

由于各种原因，删除项目



## WeChatHooker


-   [x] 自动检测登录
-   [x] 二维码生成捕获
-   [x] 用户信息memory读取
-   [x] 发送个人消息
-   [x] 发送微信文件助手
-   [x] 发送群聊消息
-   [x] 发送群聊消息 带@人
-   [x] 接受消息和解析消息
-   [x] 获取好友列表
-   [x] 获取指定群成员列表
-   [ ] 自动收款

## 依赖

cJson


websocketpp


websocket.io.cpp


## 服务

可以定制微信PC端大部分需求服务，其中包括机器人，收款等。可以定制支付平台，转账模式等，支付宝微信都可以。联系邮箱：zhaojunlike@qq.com


## 功能

目前项目功能是注入一个DLL，拦截一些hook和读取内存，dll注入后会注册一个socket client，所以只需要提供socket-server后，你便可以随心所欲控制客户端做任何事情了。DLL 不提供源码，提供typescript写的服务端，提供api文档
