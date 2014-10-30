# 推送

* :8093/app/client/device/push
* 请求参数示例：
````
{
	"baseRequest": {
		"uid": 23622391649370202,
		"deviceID": "e907195984764735",
        "token": ""
	},
    "sessions": ["all"],
	"msg": {
		"fromUserName": "23622391649370202@user",
		"toUserName": "572b768e-79f8-48e6-9cbe-4ad9db1ca6d9@qun",
		"msgType": 1,
		"content": "Test!",
        "clientMsgId": 1407734409242,
        "customFilelds":{"dataType":"1","taskType":"审批","operType":"update","content":"","appCode":"arrange"}
	}
}
````
其中的 ````"sessions": ["all"]```` 参数请参考[会话推送]()。
* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    },
    "clientMsgId": 1407734409242,
    "msgID": "msgid"
}
````
