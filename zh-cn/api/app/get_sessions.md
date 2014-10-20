# 获取会话集

* :8093/app/client/app/getSessions
* 请求参数示例：
````
{
	"baseRequest": {
		"uid": "23622391649370202",
		"deviceID": "e907195984764735",
        "deviceType": "", // iOS / Android
        "token": "23123232"
	}
}
````
该接口为获取指定 user_id的所有会话集

* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    },
    "memberList":[{
        "id": "23622391649370002_Netscape-5-0",
        "type": "23622391649370002_Netscape",
        "userId": "23622391649370002",
        "sate": "init",
        "created": "2014-10-20T03:23:20Z",
        "updated": "2014-10-20T03:23:30Z"
    }]
}
````
