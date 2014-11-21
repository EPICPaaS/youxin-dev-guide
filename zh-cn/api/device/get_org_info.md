# 获取组织机构
* :8093/app/client/device/getOrgInfo
* 请求参数示例：

````
{
   "baseRequest":
   {
      "deviceID":"000000000000000",
      "token": "23622391649384525_adcdad94-4733-46f1-92cf-88161e3a01a2",
      "uid":"23622391649384525"
   }
}
````

返回当前用户（token对应用户）所在租户的所有单位信息和该用户的好友信息

* 响应示例：

````
{
    "baseResponse": {
        "errMsg": "",
        "ret": 0
    },
    "ognizationMemberList": {
        "uid": "23622391649337822",
        "userName": "23622391649337822@tenant",
        "name": "",
        "nickName": "远信科技",
        "headImgUrl": "",
        "memberCount": 10,
        "memberList": [
            {
                "uid": "23622391649369970",
                "userName": "23622391649369970@org",
                "name": "",
                "nickName": "云办公事业部",
                "headImgUrl": "",
                "memberCount": 2,
                "memberList": [
                    {
                        "uid": "23622391649369972",
                        "userName": "23622391649369972@org",
                        "name": "",
                        "nickName": "开发部",
                        "headImgUrl": "",
                        "memberCount": 0,
                        "memberList": null,
                        "pYInitial": "",
                        "pYQuanPin": "",
                        "status": "",
                        "starFriend": 0,
                        "avatar": "",
                        "sort": 0,
                        "password": "",
                        "tenantId": "",
                        "email": "",
                        "mobile": "",
                        "area": ""
                    },
                    {
                        "uid": "23622391649369971",
                        "userName": "23622391649369971@org",
                        "name": "",
                        "nickName": "运营部",
                        "headImgUrl": "",
                        "memberCount": 0,
                        "memberList": null,
                        "pYInitial": "",
                        "pYQuanPin": "",
                        "status": "",
                        "starFriend": 0,
                        "avatar": "",
                        "sort": 0,
                        "password": "",
                        "tenantId": "",
                        "email": "",
                        "mobile": "",
                        "area": ""
                    }
                ],
                "pYInitial": "",
                "pYQuanPin": "",
                "status": "",
                "starFriend": 0,
                "avatar": "",
                "sort": 0,
                "password": "",
                "tenantId": "",
                "email": "",
                "mobile": "",
                "area": ""
            },

    "starMemberCount": 3,
    "starMemberList": [
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
        },
        {
            "uid": "23622391649370236",
            "userName": "23622391649370236@user",
            "name": "supiyun",
            "nickName": "苏丕云",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "szy",
            "pYQuanPin": "suzuoyun",
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
    "userOgnization": "23622391649369952"
}
````

