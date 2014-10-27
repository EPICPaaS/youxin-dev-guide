# 更新群主题
* 请求参数示例：
````
{
    "baseRequest" : {
        "uid": "23622391649384525",
        "deviceID": "e650854909077878",
        "deviceType": "iOS",
        "token": "23622391649384525_3664770b-a97e-4fbe-8433-08ae20267114"
    },
	"ChatRoomName": "0787f7b1-7eb4-480a-b726-5f3093a8e0d8@qun",
    "topic": "测试名称"
}
````
其中````topic````为群主题

* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": "update Qun Topic success"
    }
}
````
