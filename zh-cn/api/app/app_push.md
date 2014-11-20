# 应用推送

* :8093/app/client/app/user/push
* 请求参数示例：
````
{
    "baseRequest": {
        "token": "eflow_token"
    },
    "content": "有信测试！",
    "msgType": "102",
    "toUserNames": [
        "23622391649384526@user",
        "23622391649384525@user"
    ],
    "objectContent": {
        "appId": "2",
        "body": [
            {
                "content": "列表项1要显示的内容"
            },
            {
                "content": "列表项2要显示的内容"
            }
        ],
        "operations": [
                    {
                "content": "选项返回一个页面",
                "action": "http://192.168.2.15:8080/test/phone/test/type1",
                "msgType": "1"
            },
             {
                "content": "选项返回一个JSON",
                "action": "http://192.168.2.15:8080/test/phone/test/type2",               
		    "msgType": "2"
            }
        ],
        "head": {
            "pubTime": "1415672178725",
            "content": "测试标题2"
        }
    },
    "sessions": [
        "all"
    ],
    "expire": 3600
}
````
* 请求响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    }
}
````
* 一次调用的推送人数上限是 ````1000````
* ````token```` 在[接入](../app_join/README.md)后会分配给应用
