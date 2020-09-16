# TagResources

Creates tags and attaches them to a specified resource at a time.

## Descriptions

Tags are used to classify instances. Each tag is composed of a key-value pair. Before you attach a tag to an instance, make sure that the following requirements are met:

-   The keys of tags that are attached to the same instance must be unique.
-   After you create a tag, you must attach it to an instance.
-   Tag information is not shared across regions.

    For example, in the China \(Shanghai\) region, you cannot view tags created in the China \(Hangzhou\) region.

-   Virtual Private Cloud \(VPC\) networks, routes tables, VSwitches and elastic IP addresses \(EIPs\) that are created under the same account and in the same region share tag information.

    For example, if you have attached a tag to a VPC network, the tag is available to VSwitches, route tables, and EIPs under the same account and in the same region where the VPC network is created. You can directly select this tag from the editing page without the need to enter the tag again. You can modify the key and value of a tag, or remove a tag that is attached to an instance at any time. After you delete an instance, all tags that are attached to the instance are removed.

-   You can attach up to 20 tags to each instance. Before you attach a tag to an instance, the system automatically checks the existing tags. If the maximum number of tags is reached, an error message is returned.

## Debugging

[OpenAPI Explorer automatically calculates the signature value. For your convenience, we recommend that you call this operation in OpenAPI Explorer. OpenAPI Explorer dynamically generates a sample code of the operation for different SDKs.](https://api.aliyun.com/#product=Vpc&api=TagResources&type=RPC&version=2016-04-28)

## Request parameters

|Parameter|Type|Required|Example|Description|
|---------|----|--------|-------|-----------|
|Action|String|Yes|TagResources|The operation that you want to perform. Set the value to **TagResources**. |
|RegionId|String|Yes|cn-hangzhou|The region ID of the resource. |
|ResourceId.N|RepeatList|Yes|vpc-bp16qjewdsunr41m1\*\*\*\*|The ID of the resource. Valid values of N: 1 to 20. |
|ResourceType|String|Yes|VPC|The type of the resource. Valid values:

 -   **VPC**: VPC network.
-   **VSWITCH**: VSwitch.
-   **ROUTETABLE**: route table.
-   **EIP**: EIP.
-   **VpnGateway**: VPN gateway. |
|Tag.N.Key|String|No|FinanceDept|The tag key. Valid values of N: 1 to 20. The tag key cannot be an empty string. The key must be 1 to 64 characters in length, and start with a letter or Chinese character. It can contain numbers, periods \(.\), underscores \(\_\), and hyphens \(-\) and cannot start with `aliyun` or `acs:`. It cannot contain `http://` or `https://`. |
|Tag.N.Value|String|No|FinanceJoshua|The tag key of the resource. Valid values of N: 1 to 20. The tag value can be an empty string. The key must be 1 to 128 characters in length, and start with a letter or Chinese character. It can contain numbers, periods \(.\), underscores \(\_\), and hyphens \(-\) and cannot start with `aliyun` or `acs:`. It cannot contain `http://` or `https://`. |

## Response parameters

|Parameter|Type|Example|Description|
|---------|----|-------|-----------|
|RequestId|String|C46FF5A8-C5F0-4024-8262-B16B639225A0|The request ID. |

## Example

Sample requests

```
http(s)://vpc.aliyuncs.com/? Action=TagResources
&RegionId=cn-hangzhou
&ResourceId.1=vpc-bp16qjewdsunr41m1****
&ResourceType=VPC
&Tag.1.Key=FinanceDept
&Tag.1.Value=FinanceJoshua
&<Common request parameters>
```

Sample success responses

`XML` format

```
<TagResourcesResponse>
      <RequestId>C46FF5A8-C5F0-4024-8262-B16B639225A0</RequestId>
</TagResourcesResponse>
```

`JSON` format

```
{
	"RequestId":"C46FF5A8-C5F0-4024-8262-B16B639225A0"
}
```

## Error codes

|HttpCode|Error code|Error message|Description|
|--------|----------|-------------|-----------|
|403|Forbidden|User not authorized to operate on the specified resource.|The error message returned because you are not authorized to perform this operation on the specified resource. To acquire the required permissions, submit a ticket.|

For a list of error codes, visit the [API Error Center](https://error-center.alibabacloud.com/status/product/Vpc).

