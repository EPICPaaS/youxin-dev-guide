# 网页消息客户端接口使用办法


TBD

* 处于安全性考虑，不在网页消息客户端中提供推送相关接口，只提供消息获取接口

 1 、引入msg-js.js

 2、新建gopushCli客户端，代码示例：

````
    var channel = new GoPushCli({

        host: '10.180.120.63',
        port: 8090,
        key: '23622391649370202@user',
        onOfflineMessage: function (data) {//接收到离线消息时触发
            addContent(decodeURIComponent(data.msg));
        },
        onOnlineMessage: function (data) { //接受到在线消息时触发
            addContent(decodeURIComponent(data.msg));
        },
        onError: function (message) { //异常时触发
            addContent(message);
        },
        onOpen: function (message) {//打开连接时触发
            addContent('初始化完成');
        },
        onClose: function (message) {//断开连接时触发
            addContent('连接断开');
        }
    });
````

其中

````host```` 值为消息服务器地址；
````port```` 值为消息服务器监听端口；
````key```` 的值由{user_id}+@user组成；


 3、启动客户端监听,代码示例：
````
    //启动gopushCli
    channel.start();
````
 4、 注销客户端连接，代码示例：
````
    //销毁gopushCli
    channel.destory();
````


