# 设备推送

* :8093/app/client/device/push
* 请求参数示例：
````
{
	"baseRequest" : {
		"uid" : 23622391649370202,
		"deviceID" : "e907195984764735",
        "token": ""
	},
	"msg" : {
		"fromUserName" : "23622391649370202@user",
		"toUserName" : "572b768e-79f8-48e6-9cbe-4ad9db1ca6d9@qun",
		"msgType" : 1,
		"content" : "Test!",
        "clientMsgId" : 1407734409242
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

