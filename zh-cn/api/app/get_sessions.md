# 获取会话集
* :8093/app/client/app/getSessions
* 请求参数示例：
````
{
	"baseRequest": {
		"uid": 23622391649370202,
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
       "id":"23622391649370012_Netscape",
       "type":"IOS",
       "userId":"211323231321",
       "sate","active"
       "created":2014-10-20 02:40:24
       "updated":2014-10-20 02:40:25
    },{
       "id":"23622391649370013_Netscape",
       "type":"Android",
       "userId":"211323231321",
       "sate","inactive"
       "created":2014-10-20 01:40:24
       "updated":2014-10-20 01:40:25
    }]
}
````
