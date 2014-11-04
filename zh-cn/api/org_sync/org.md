# 组织同步
* :8093/app/client/app/syncOrg
* 请求参数示例：
````
{
    "baseRequest" : {
        "token": "hris_token"
    },
	"org": {
        "id": "11111",
        "name": "财务部测试",
        "shortName": "caiwu",
        "parentId": "1222222222222",
        "tenantId": "23622391649337822",
        "location": "00",
        "sort":1
    }
}
````
响应示例：
````
{
    "baseResponse": {
        "errMsg": "syncOrg succeed",
        "ret": 0
    }
}
