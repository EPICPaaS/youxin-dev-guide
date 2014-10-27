# 添加 APNS Token

这个接口只有 iOS 设备会使用到。
* :8093/app/client/device/addApnsToken
* 请求参数示例：

````
{

    "baseRequest": {
        "deviceID": "22222",
        "deviceType": "Android",
        "token": "23622391649384525_07f18ae8-837a-402b-b022-78d5230c95fd",
        "uid": "23622391649384525"
    },

    "apns_token":"22222"

}
````

* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": "save apns_token success"
    }
}
````
