# 公共参数

## 参数格式约定

**输入参数**和**返回参数**都是 JSON 格式的。属性名以小写字母开头、驼峰式，例如：

````
{
    "baseRequest" : {
        "uid": "",
        "deviceType": "",
        "deviceID": "",
        "token": ""
    },
	"userName": "",
    "password": ""
}
````

## baseRequest

每次调用请求都包含一个公共结构 ````baseRequest````：
````
{
    "baseRequest" : {
        "uid": "",
        "deviceType": "",
        "deviceID": "",
        "token": ""
    },
	....
}
````
其中：

* ````uid````：用户 id
* ````deviceType````: android/iOS/appWeb
* ````deviceID````：设备 id
* ````token````：调用令牌

## baseResponse

每次调用请求返回参数都包含一个公告结构 ````baseResponse````：
````
{
    "baseResponse": {
        "ret": 0,
        "errMsg": ""
    },
    ....
}
````
其中：

* ````ret````：[返回码](ret.md)
* ````errMsg````：错误信息

## userName@后缀

* @user：用户
* @tenant：组织机构-单位
* @org：组织机构-部门
* @qun：群
* @app：应用

## HTTP Method

若无特殊说明，接口的 HTTP 方法均为 POST.
















