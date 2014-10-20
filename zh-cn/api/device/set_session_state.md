# 设置会话状态

* :8093/app/client/device/setSessionState
* 请求参数示例：
````
{
	"baseRequest": {
		"uid": 23622391649370202,
		"deviceID": "e907195984764735",
        "deviceType": "", // iOS / Android
        "token": ""
	},
    "state":"active",
    "sessionId":"1111"
}
````
其中的 ````"state":"active"```` 参数为会话状态，有两种值:`active`（激活会话）、 `inactive`（注销会话）;
````"sessionId":"1111"```` 参数为会话 id。

* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    }
}
````
