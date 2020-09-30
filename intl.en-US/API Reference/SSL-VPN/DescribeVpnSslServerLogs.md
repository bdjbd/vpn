# DescribeVpnSslServerLogs

Queries the logs of an SSL-VPN server.

## Debugging

[OpenAPI Explorer automatically calculates the signature value. For your convenience, we recommend that you call this operation in OpenAPI Explorer. OpenAPI Explorer dynamically generates the sample code of the operation for different SDKs.](https://api.aliyun.com/#product=Vpc&api=DescribeVpnSslServerLogs&type=RPC&version=2016-04-28)

## Request parameters

|Parameter|Type|Required|Example|Description|
|---------|----|--------|-------|-----------|
|Action|String|Yes|DescribeVpnSslServerLogs|The operation that you want to perform. Set the value to **DescribeVpnSslServerLogs**. |
|RegionId|String|Yes|cn-hangzhou|The region ID of the SSL-VPN server. You can call the [DescribeRegions](~~36063~~) operation to query region IDs. |
|VpnSslServerId|String|Yes|vss-bp155e9yclsg1xgq4\*\*\*\*|The ID of the SSL-VPN server. |
|From|Integer|No|1600738962|The start time of the log. Only second-level Unix timestamps are supported. For example, 1600738962 indicates that the log started from 9:42:42\(UTC\), September 22, 2020.

 **Note:** If the **From** parameter is set, you must set the **To** or **MinutePeriod** parameter. |
|To|Integer|No|1600738962|The end time of the log. Only second-level Unix timestamps are supported. For example, 1600738962 indicates that the log ended at 9:42:42\(UTC\), September 22, 2020.

 **Note:** If the **From** parameter is set, you must set the **To** or **MinutePeriod** parameter. |
|MinutePeriod|Integer|No|10|The recording cycle of the logs.

 **Note:** If the **From** and **To** parameters are not set, you must set the **MinutePeriod** parameter. |
|PageNumber|Integer|No|1|The number of the page to return. Default value: **1**. |
|PageSize|Integer|No|10|The number of entries to return on each page. Maximum value: **50**. Default value: **10**. |

## Response parameters

|Parameter|Type|Example|Description|
|---------|----|-------|-----------|
|Count|Integer|10|The number of log entries. |
|Data|List|test|An array of log entries. Each item in the array indicates a log entry. |
|IsCompleted|Boolean|true|Indicates whether the log is accurate. Valid values:

 -   **true**: accurate
-   **false**: inaccurate |
|PageNumber|Integer|1|The number of the returned page. |
|PageSize|Integer|1|The number of entries returned per page. |
|RequestId|String|5BE01CD7-5A50-472D-AC14-CA181C5C03BE|The request ID. |

## Examples

Sample request

```
http(s)://[Endpoint]/? Action=DescribeVpnSslServerLogs
&RegionId=cn-hangzhou
&VpnSslServerId=vss-bp155e9yclsg1xgq4****
&<Common request parameters>
```

Sample success responses

`XML` format

```
<DescribeVpnSslServerLogsResponse>
	  <Data></Data>
	  <PageNumber>1</PageNumber>
	  <Count>0</Count>
	  <PageSize>10</PageSize>
	  <IsCompleted>true</IsCompleted>
	  <RequestId>26641E42-66C7-4942-9FEC-F99213914F8F</RequestId>
</DescribeVpnSslServerLogsResponse>
```

`JSON` format

```
{
	"Data": {
		"Logs": []
	},
	"PageNumber": 1,
	"Count": 0,
	"PageSize": 10,
	"IsCompleted": true,
	"RequestId": "26641E42-66C7-4942-9FEC-F99213914F8F"
}
```

## Error codes

|HttpCode|Error code|Error message|Description|
|--------|----------|-------------|-----------|
|403|Forbbiden.SubUser|User not authorized to operate on the specified resource as your account is created by another user.|The error message returned because you are not authorized to perform this operation on the specified resource. You can apply for the permission and try again.|
|403|Forbidden|User not authorized to operate on the specified resource.|The error message returned because you are not authorized to perform this operation on the specified resource. To acquire the required permissions, submit a ticket.|

For a list of error codes, visit the [API Error Center](https://error-center.alibabacloud.com/status/product/Vpc).

