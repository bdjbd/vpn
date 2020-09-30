# Limits

This topic describes the limits on using VPN gateways. Before you use a VPN gateway, note the following limits.

## Instance limits

|Item|Limit|Adjustable|
|----|-----|----------|
|Number of VPN gateways that can be created for each account|30 **Note:** The maximum number of VPN gateways that can be created is determined by the account, regardless of the region where the VPN gateways are deployed or the VPC networks to which the VPN gateways belong.

For example, for each account:

-   You can create up to 30 VPN gateways that are deployed in a Virtual Private Cloud \(VPC\) network within a region.
-   You can create up to 30 VPN gateways that are deployed in multiple VPC networks across multiple regions.

|Go to the [Quota Management page](https://vpc.console.aliyun.com/quota) and request a quota increase. For more information, see [Manage quotas](/intl.en-US/User Guide/Manage quotas.md). |
|Number of policy-based routes that can be created for each VPN gateway|20|
|Number of destination-based routes that can be created for each VPN gateway|20|

## Customer gateways

|Item|Limit|Adjustable|
|----|-----|----------|
|Number of customer gateways that can be created in a region|100|N/A|

## IPsec-VPN connections

|Item|Limit|Adjustable|
|----|-----|----------|
|Number of IPsec-VPN connections that can be created for each VPN gateway|10|Go to the [Quota Management page](https://vpc.console.aliyun.com/quota) and request a quota increase. For more information, see [Manage quotas](/intl.en-US/User Guide/Manage quotas.md). |
|Maximum bandwidth that each IPsec-VPN connection supports|200M**Note:** If the maximum bandwidth of a VPN gateway is higher than 200 Mbit/s, you can create multiple IPsec-VPN connections to make full use of the bandwidth of the VPN gateway. For more information, see [How to make full use of VPN Gateway bandwidth](/intl.en-US/FAQ/VPN Gateway FAQ.md).

|N/A|
|Number of source CIDR blocks that can be added to each IPsec-VPN connection|5|
|Number of destination CIDR blocks that can be added to each IPsec-VPN connection|5|

## SSL-VPN connections

|Item|Limit|Adjustable|
|----|-----|----------|
|Number of SSL client certificates that each account can reserve|50|Go to the [Quota Management page](https://vpc.console.aliyun.com/quota) and request a quota increase. For more information, see [Manage quotas](/intl.en-US/User Guide/Manage quotas.md). |
|Number of SSL servers that can be associated with each VPN gateway|1|N/A|
|Number of source CIDR blocks that can be added to each SSL server|5|
|Number of destination CIDR blocks that can be added to each SSL server|1|
|Ports that are not supported by SSL servers|22, 2222, 22222, 9000, 9001, 9002, 7505, 80, 443, 53, 68, 123, 4510, 4560, 500, and 4500|
|Validity period of an SSL client certificate|Three years|

