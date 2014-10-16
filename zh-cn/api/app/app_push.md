# 应用推送

* :8093/app/client/app/user/push
* 请求参数示例：
````
{
	"baseRequest" : {
         "token": "eflow_token"
	},
    "sessions": ["all"],
    "content": "Test!",
    "msgType": "1",
	"toUserNames" : ["22622391649384526@user", "22622391649384527@user"],
    "objectContent": {
        "appId": "23622391649370202",
        "appSendId": "xxxxx"
    }
}
````
* 请求响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    }
}
````
* 一次调用的推送人数上限是 ````1000````
* ````token```` 在[接入](../app_join/README.md)后会分配给应用
