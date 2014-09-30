# 用户登录

* :8093/app/client/device/login
* 请求参数示例：
````
{
    "baseRequest" : {
        "uid": "",
        "deviceID": "",
        "token": ""
    },
	"userName": "dingliang",
    "password": "1"
}
````
* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    },
    "member": {
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
        "password": "",
        "tenantId": "23622391649337822",
        "email": "",
        "mobile": "",
        "area": ""
    },
    "token": "23622391649370202_a46adc6d-b4a8-46f0-a6a0-f09fc6259a55",
    "uid": "23622391649370202"
}
````

## token

登录后的后续 APIs 调用都需要使用 ````token````，所以这个 ````token```` 需要客户端设备进行临时保存。

在不调用任何 API 半小时后 ````token```` 会自动过期，需要进行重新登录。

应用不需要调用登录接口，在需要推送消息时直接调用应用推送接口即可。
