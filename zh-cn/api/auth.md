# 调用授权

通过 ````token```` 验证调用者是否有调用权限。

````token```` 在公共参数的 ````baseRequest```` 中，[用户登录](login.md)后会返回一个可用的 token，后续请求时需要带上这个 token。

如果调用者是_应用_，则需要提前人工申请 token，进行[应用接入](../app_join/README.md)。
