# List of operations by function

The following tables list the API operations that are available for use in VPN Gateway. The endpoint of the VPN Gateway API is `vpc.aliyuncs.com`. For more information, see the Call APIs topic in API Reference for Virtual Private Cloud \(VPC\).

## VPN gateways

|API|Description|
|---|-----------|
|[t2556.md\#](/intl.en-US/API reference/VPN Gateway/CreateVpnGateway.md)|Creates a VPN gateway.|
|[t2558.md\#](/intl.en-US/API reference/VPN Gateway/ModifyVpnGatewayAttribute.md)|Modifies the name and description of a VPN gateway.|
|[t2557.md\#](/intl.en-US/API reference/VPN Gateway/DescribeVpnGateways.md)|Queries VPN gateways.|
|[t2757.md\#](/intl.en-US/API reference/VPN Gateway/DescribeVpnGateway.md)|Queries details about a VPN gateway.|
|[t2559.md\#](/intl.en-US/API reference/VPN Gateway/DeleteVpnGateway.md)|Deletes a VPN gateway|
|[TagResources](/intl.en-US/API reference/Tag/TagResources.md)|Creates and attaches tags to the specified VPN gateways.|
|[ListTagResources](/intl.en-US/API reference/Tag/ListTagResources.md)|Queries tags that are attached to the specified VPN gateways.|
|[UnTagResources](/intl.en-US/API reference/Tag/UnTagResources.md)|Removes tags from the specified VPN gateways.|

## Customer gateways

|API|Description|
|---|-----------|
|[t2560.md\#](/intl.en-US/API reference/VPN Gateway/CreateCustomerGateway.md)|Creates a customer gateway.|
|[t2564.md\#](/intl.en-US/API reference/VPN Gateway/ModifyCustomerGatewayAttribute.md)|Modifies the name and description of a customer gateway.|
|[t2561.md\#](/intl.en-US/API reference/VPN Gateway/DescribeCustomerGateways.md)|Queries customer gateways.|
|[t2562.md\#](/intl.en-US/API reference/VPN Gateway/DescribeCustomerGateway.md)|Queries details about a customer gateway.|
|[t2563.md\#](/intl.en-US/API reference/VPN Gateway/DeleteCustomerGateway.md)|Deletes a customer gateway.|

## Routes for VPN gateways

|API|Description|
|---|-----------|
|[CreateVpnRouteEntry](/intl.en-US/API reference/VPN Gateway/CreateVpnRouteEntry.md)|Creates a destination-based route entry for a VPN gateway.|
|[CreateVpnPbrRouteEntry](/intl.en-US/API reference/VPN Gateway/CreateVpnPbrRouteEntry.md)|Creates a policy-based route entry for a VPN gateway.|
|[PublishVpnRouteEntry](/intl.en-US/API reference/VPN Gateway/PublishVpnRouteEntry.md)|Publishes a route entry of a VPN gateway to the route table of the associated VPC network.|
|[DescribeVpnRouteEntries](/intl.en-US/API reference/VPN Gateway/DescribeVpnRouteEntries.md)|Queries destination-based route entries of a VPN gateway.|
|[DescribeVpnPbrRouteEntries](/intl.en-US/API reference/VPN Gateway/DescribeVpnPbrRouteEntries.md)|Queries policy-based route entries of a VPN gateway.|
|[ModifyVpnRouteEntryWeight](/intl.en-US/API reference/VPN Gateway/ModifyVpnRouteEntryWeight.md)|Modifies the weight of a destination-based route entry for a VPN gateway.|
|[ModifyVpnPbrRouteEntryWeight](/intl.en-US/API reference/VPN Gateway/ModifyVpnPbrRouteEntryWeight.md)|Modifies the weight of a policy-based route entry for a VPN gateway.|
|[DeleteVpnRouteEntry](/intl.en-US/API reference/VPN Gateway/DeleteVpnRouteEntry.md)|Deletes a destination-based route entry of a VPN gateway.|
|[DeleteVpnPbrRouteEntry](/intl.en-US/API reference/VPN Gateway/DeleteVpnPbrRouteEntry.md)|Deletes a policy-based route entry of a VPN gateway.|

## IPsec-VPN

|API|Description|
|---|-----------|
|[t2565.md\#](/intl.en-US/API reference/VPN Gateway/CreateVpnConnection.md)|Creates an IPsec-VPN connection.|
|[t2568.md\#](/intl.en-US/API reference/VPN Gateway/ModifyVpnConnectionAttribute.md)|Modifies the configuration of an IPsec-VPN connection.|
|[DescribeVpnConnections](/intl.en-US/API reference/VPN Gateway/DescribeVpnConnections.md)|Queries IPsec-VPN connections.|
|[t2567.md\#](/intl.en-US/API reference/VPN Gateway/DescribeVpnConnection.md)|Queries details about an IPsec-VPN connection.|
|[t2570.md\#](/intl.en-US/API reference/VPN Gateway/DownloadVpnConnectionConfig.md)|Downloads the configuration of an IPsec-VPN connection.|
|[t2569.md\#](/intl.en-US/API reference/VPN Gateway/DeleteVpnConnection.md)|Deletes an IPsec-VPN connection.|

## SSL-VPN

|API|Description|
|---|-----------|
|[t2571.md\#](/intl.en-US/API reference/VPN Gateway/CreateSslVpnServer.md)|Creates an SSL-VPN server.|
|[t2574.md\#](/intl.en-US/API reference/VPN Gateway/ModifySslVpnServer.md)|Modifies the configuration of an SSL-VPN server.|
|[t2572.md\#](/intl.en-US/API reference/VPN Gateway/DescribeSslVpnServers.md)|Queries SSL-VPN servers.|
|[t2573.md\#](/intl.en-US/API reference/VPN Gateway/DeleteSslVpnServer.md)|Deletes an SSL-VPN server.|
|[t2575.md\#](/intl.en-US/API reference/VPN Gateway/CreateSslVpnClientCert.md)|Creates an SSL-VPN client certificate.|
|[t2578.md\#](/intl.en-US/API reference/VPN Gateway/ModifySslVpnClientCert.md)|Modifies the name of an SSL-VPN client certificate.|
|[t2576.md\#](/intl.en-US/API reference/VPN Gateway/DescribeSslVpnClientCerts.md)|Queries SSL-VPN client certificates.|
|[DescribeVpnSslServerLogs](/intl.en-US/API reference/VPN Gateway/DescribeVpnSslServerLogs.md)|Queries the logs of an SSL server.|
|[t2577.md\#](/intl.en-US/API reference/VPN Gateway/DeleteSslVpnClientCert.md)|Deletes an SSL-VPN client certificate.|

