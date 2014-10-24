# 获取群用户

* :8093/app/client/device/getQunMembers
* 请求参数示例：
````
{
    "baseRequest" : {
        "uid": "23622391649384525",
        "deviceID": "e650854909077878",
        "token": "23622391649384525_3664770b-a97e-4fbe-8433-08ae20267114"
    },
	"userName": "0787f7b1-7eb4-480a-b726-5f3093a8e0d8@qun"
}
````


* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    },
    "memberCount": 6,
    "memberList": [
        {
            "uid": "23622391649370112",
            "userName": "23622391649370112@user",
            "name": "zhangyou",
            "nickName": "张友",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "zy",
            "pYQuanPin": "zhangyou",
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
            "uid": "23622391649370150",
            "userName": "23622391649370150@user",
            "name": "huhongwei",
            "nickName": "胡宏伟",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "hhw",
            "pYQuanPin": "huhongwei",
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
            "uid": "23622391649370202",
            "userName": "23622391649370202@user",
            "name": "dingliang",
            "nickName": "丁亮",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "dl",
            "pYQuanPin": "dingliang",
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
            "uid": "23622391649370234",
            "userName": "23622391649370234@user",
            "name": "guohuagang",
            "nickName": "郭华刚",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "ghg",
            "pYQuanPin": "guohuagang",
            "status": "1",
            "starFriend": 0,
            "avatar": "C8EC897377B20A126D6D0A6D6D0A6DB20A8FECE1D78A6",
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
        },
        {
            "uid": "23622391649384526",
            "userName": "23622391649384526@user",
            "name": "liuxue",
            "nickName": "刘学",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "lx",
            "pYQuanPin": "liuxue",
            "status": "1",
            "starFriend": 0,
            "avatar": "",
            "sort": 0,
            "password": "",
            "tenantId": "23622391649337822",
            "email": "",
            "mobile": "",
            "area": ""
        }
    ],
    "quninfo": {
        "id": "0787f7b1-7eb4-480a-b726-5f3093a8e0d8",
        "creatorId": "23622391649384526",
        "creatorUserName": "23622391649384526@user",
        "name": "我的群 test tips",
        "description": "",
        "maxMember": 100,
        "avatar": "",
        "created": "2014-10-23T09:28:03Z",
        "updated": "2014-10-23T09:28:03Z"
    }
}
````
