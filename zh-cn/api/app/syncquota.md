# 同步配额信息

* :8093/app/client/app/syncQuota
* 请求参数示例：
````
{
    "baseRequest" : {
        "token": "eflow_token"
    },
	"quata": {
	   "customerId":"22222",
	   "tenantId":"2222",
	   "apiName":"/app/client/device/push",
       "type":"push_cnt",
	   "value":"23"
    }
}
````
其中```` "type"````的类型有```` api_cnt(API 调用计数)/push_cnt(推送计数)/expire(到期时间 )````

* 响应示例：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    }
}
````

