# 获取离线消息

* :8090/1/msg/get?k=23622391649370226@user&m=0&token=xxxxx
* 使用 HTTP _GET_ 方法
* 请求响应示例：
````
{
    "data":{
        "msgs":[
            {"msg":{"test":2},"mid":1411961991613967,"gid":0}
        ]
    },
    "ret":0
}
````
* 指定查询参数中的 ````m```` 用于消息过滤，只会获取到 ````mid```` 大于等于该实参的离线消息
* Web 网页上请使用 [JS  客户端](../scene_usages/web/README.md)进行开发
