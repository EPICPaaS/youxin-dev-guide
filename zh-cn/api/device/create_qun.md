# 创建群

* :8093/app/client/device/create-qun
* 请求参数示例：
````
{
    "baseRequest" : {
        "uid": "23622391649384525",
        "deviceID": "e650854909077878",
        "token": "23622391649384525_3fd4561d-d9ff-4329-a194-71d206527f6b"
    },
    "topic" : "test-topic",
    "memberCount" : 2,
    "memberList" : [{
			"uid" : "23622391649384525",
			"userName" : "23622391649384525@user"
		}, {
			"uid" : "23622391649370204",
			"userName" : "23622391649370204@user"
		}
	]
}
````


* 响应示例：
````
{
    "ChatRoomName": "ca50ed67-f650-48b1-9eac-c7860778019f@qun",
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    },
    "memberCount": 2,
    "memberList": [
        {
            "uid": "23622391649370204",
            "userName": "23622391649370204@user",
            "name": "dingyi",
            "nickName": "丁毅",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "dy",
            "pYQuanPin": "dingyi",
            "status": "1",
            "starFriend": 0,
            "avatar": "",
            "sort": 0,
            "password": "",
            "tenantId": "23622391649337822",
            "email": "",
            "mobile": "",
            "area": ""
        },
        {
            "uid": "23622391649384525",
            "userName": "23622391649384525@user",
            "name": "renhang",
            "nickName": "任航",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "rh",
            "pYQuanPin": "renhang",
            "status": "1",
            "starFriend": 0,
            "avatar": "C8EC897377B20A126D6D0A6D6D0A6DB20A8FECE1D78A6",
            "sort": 0,
            "password": "",
            "tenantId": "23622391649337822",
            "email": "",
            "mobile": "",
            "area": ""
        }
    ],
    "topic": "test-topic"
}
````
