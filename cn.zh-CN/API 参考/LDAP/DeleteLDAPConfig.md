# DeleteLDAPConfig {#doc_api_NAS_DeleteLDAPConfig .reference}

用于删除LDAP设置。

## 调试 {#api_explorer .section}

[您可以在OpenAPI Explorer中直接运行该接口，免去您计算签名的困扰。运行成功后，OpenAPI Explorer可以自动生成SDK代码示例。](https://api.aliyun.com/#product=NAS&api=DeleteLDAPConfig&type=RPC&version=2017-06-26)

## 请求参数 {#parameters .section}

|名称|类型|是否必选|示例值|描述|
|--|--|----|---|--|
|Action|String|是|DeleteLDAPConfig|系统规定参数。取值：DeleteLDAPConfig。

 |
|FileSystemId|String|是|1ca404a348|文件系统ID。

 |

## 返回数据 {#resultMapping .section}

|名称|类型|示例值|描述|
|--|--|---|--|
|RequestId|String|5B4511A7-C99E-4071-AA8C-32E2529DA963|请求ID。

 |

## 示例 {#demo .section}

请求示例

``` {#request_demo}

GET https://nas.cn-hangzhou.aliyuncs.com/?Action=DeleteLDAPConfig
&FileSystemId=cpfs-xxx
&URI=[ldap://ldap.example.example](需做URLEncode)
&<公共请求参数>

```

正常返回示例

`XML` 格式

``` {#xml_return_success_demo}
<DeleteLDAPConfigResponse>
    <RequestId>5B4511A7-C99E-4071-AA8C-32E2529DA963</RequestId>
</DeleteLDAPConfigResponse>
```

`JSON` 格式

``` {#json_return_success_demo}
{
	"RequestId":"5B4511A7-C99E-4071-AA8C-32E2529DA963"
}
```

## 错误码 { .section}

访问[错误中心](https://error-center.aliyun.com/status/product/NAS)查看更多错误码。

