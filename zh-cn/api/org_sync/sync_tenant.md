# 同步租户
* :8093/app/client/app/syncTenant
* 请求参考示例：

````
{
    "baseRequest" : {
        "token": "hris_token"
    },
	"tennat": {
	   "id":"",
	   "code":"222",
	   "name":"222",
	   "status":1,
	   "customerId":"223231"

    }
}
````
其中```` "customerId"```` 为有信客户ID

响应参考示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    }
}
````

