# 删除群用户

* :8093/app/client/device/delQunMember
* 请求参数示例：
````
{

    "baseRequest": {
        "deviceID": "000000000000000",
        "deviceType": "Android",
        "token": "23622391649384526_32a461d5-88a6-431f-a57f-e994f1c22b47",
        "uid": "23622391649384526"
    },
    "ChatRoomName": "7043b15d-51ff-4a05-ab33-3a60bcbab653@qun",
    "memberList": [
        {
            "sort": 0,
            "typeOrg": false,
            "typeQun": false,
            "typeTenant": false,
            "typeUser": true,
            "alias": null,
            "userName": "23622391649370104@user",
            "city": null,
            "displayName": null,
            "email": "",
            "headImgUrl": "",
            "uid": "23622391649370104",
            "memberList": null,
            "mobile": "",
            "Name": null,
            "nickName": "杨云洁",
            "pYInitial": "yyj",
            "pYQuanPin": "yangyunjie",
            "province": null,
            "remarkName": null,
            "remarkPYInitial": null,
            "remarkPYQuanPin": null,
            "signature": null,
            "sex": 0,
            "starFriend": 0,
            "status": 1,
            "memberCount": 0,
            "appAccountFlag": 0,
            "verifyFlag": 0
        }
    ]
}
````


* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    },
    "memberCount": 3,
    "memberList": [
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
        "id": "7043b15d-51ff-4a05-ab33-3a60bcbab653",
        "creatorId": "23622391649384526",
        "creatorUserName": "23622391649384526@user",
        "name": "我的群",
        "description": "",
        "maxMember": 100,
        "avatar": "",
        "created": "2014-10-23T03:34:39Z",
        "updated": "2014-10-23T03:34:39Z"
    }
}
````
