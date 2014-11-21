# 获取组织机构用户
* :8093/app/client/device/getOrgUserList
* 请求参数示例：

````
{"baseRequest":
  {
    "deviceID":"000000000000000",
    "token": "23622391649384525_adcdad94-4733-46f1-92cf-88161e3a01a2",
    "uid":"23622391649384525"
 },
 "orgid":"23622391649369952"
}
````

返回结果仅包含````orgid````部门层级的人员信息，不包含孩子部门的人员信息

* 响应示例：

````
{
    "baseResponse": {
        "errMsg": "",
        "ret": 0
    },
    "memberCount": 2,
    "memberList": [
        {
            "uid": "23622391649370398",
            "userName": "23622391649370398@user",
            "name": "fukaifei",
            "nickName": "符开飞",
            "headImgUrl": "",
            "memberCount": 0,
            "memberList": null,
            "pYInitial": "fkf",
            "pYQuanPin": "fukaifei",
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
    ]
}
````
