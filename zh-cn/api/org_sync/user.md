# 用户同步
* :8093/app/client/app/syncUser
* 请求参数示例：
````
{
    "baseRequest" : {
        "token": "hris_token"
    },
    "orgId": "123",
	"member": {
        "uid": "1",
        "userName": "111@user",
        "name": "ceishi",
        "nickName": "ceshi",
        "pYInitial": "cs",
        "pYQuanPin": "ceshi",
        "status": "1",
        "avatar": "1",
        "sort": 0,
        "password": "22",
        "tenantId": "23622391649337822",
        "email": "22",
        "mobile": "22",
        "area": "22"
    }
}
````
其中````"orgId"````为可选参数，若存在````"orgId"````参数，则将该用户添加到````"orgId"````指定的单位下。

响应示例：
````
{
    "baseResponse": {
        "errMsg": "syncUser  success",
        "ret": 0
    }
}
````
