# API概览

VPN网关提供如下API供您使用。VPN网关的API服务地址为`vpc.aliyuncs.com`，请参考VPC API文档调用VPN网关API。

## VPN网关

|API|说明|
|---|--|
|[t2556.md\#](/intl.zh-CN/API参考/VPN网关/CreateVpnGateway.md)|创建VPN网关。|
|[t2558.md\#](/intl.zh-CN/API参考/VPN网关/ModifyVpnGatewayAttribute.md)|修改VPN网关的名称和描述信息。|
|[t2557.md\#](/intl.zh-CN/API参考/VPN网关/DescribeVpnGateways.md)|查询已创建的VPN网关。|
|[t2757.md\#](/intl.zh-CN/API参考/VPN网关/DescribeVpnGateway.md)|查询指定VPN网关的详细信息。|
|[t2559.md\#](/intl.zh-CN/API参考/VPN网关/DeleteVpnGateway.md)|删除VPN网关。|
|[TagResources](/intl.zh-CN/API参考/标签/TagResources.md)|为指定的资源统一创建并绑定标签。|
|[ListTagResources](/intl.zh-CN/API参考/标签/ListTagResources.md)|查询云资源已经绑定的标签列表。|
|[UnTagResources](/intl.zh-CN/API参考/标签/UnTagResources.md)|为指定的资源列表统一解绑标签。|

## 用户网关

|API|说明|
|---|--|
|[t2560.md\#](/intl.zh-CN/API参考/VPN网关/CreateCustomerGateway.md)|创建用户网关。|
|[t2564.md\#](/intl.zh-CN/API参考/VPN网关/ModifyCustomerGatewayAttribute.md)|修改用户网关的名称和描述信息。|
|[t2561.md\#](/intl.zh-CN/API参考/VPN网关/DescribeCustomerGateways.md)|查询已创建的用户网关。|
|[t2562.md\#](/intl.zh-CN/API参考/VPN网关/DescribeCustomerGateway.md)|查询已创建的用户网关的详细信息。|
|[t2563.md\#](/intl.zh-CN/API参考/VPN网关/DeleteCustomerGateway.md)|删除指定的用户网关。|

## VPN网关路由

|API|说明|
|---|--|
|[CreateVpnRouteEntry](/intl.zh-CN/API参考/VPN网关/CreateVpnRouteEntry.md)|创建VPN目的路由。|
|[CreateVpnPbrRouteEntry](/intl.zh-CN/API参考/VPN网关/CreateVpnPbrRouteEntry.md)|创建VPN策略路由。|
|[PublishVpnRouteEntry](/intl.zh-CN/API参考/VPN网关/PublishVpnRouteEntry.md)|发布VPN路由到VPC。|
|[DescribeVpnRouteEntries](/intl.zh-CN/API参考/VPN网关/DescribeVpnRouteEntries.md)|查询VPN目的路由。|
|[DescribeVpnPbrRouteEntries](/intl.zh-CN/API参考/VPN网关/DescribeVpnPbrRouteEntries.md)|查询VPN策略路由。|
|[ModifyVpnRouteEntryWeight](/intl.zh-CN/API参考/VPN网关/ModifyVpnRouteEntryWeight.md)|修改VPN目的路由的权重值。|
|[ModifyVpnPbrRouteEntryWeight](/intl.zh-CN/API参考/VPN网关/ModifyVpnPbrRouteEntryWeight.md)|修改VPN策略路由的权重值。|
|[DeleteVpnRouteEntry](/intl.zh-CN/API参考/VPN网关/DeleteVpnRouteEntry.md)|删除VPN目的路由。|
|[DeleteVpnPbrRouteEntry](/intl.zh-CN/API参考/VPN网关/DeleteVpnPbrRouteEntry.md)|删除VPN策略路由。|

## IPsec-VPN

|API|说明|
|---|--|
|[t2565.md\#](/intl.zh-CN/API参考/VPN网关/CreateVpnConnection.md)|创建IPsec连接。|
|[t2568.md\#](/intl.zh-CN/API参考/VPN网关/ModifyVpnConnectionAttribute.md)|修改IPsec连接的配置信息。|
|[DescribeVpnConnections](/intl.zh-CN/API参考/VPN网关/DescribeVpnConnections.md)|查询已创建的IPsec连接。|
|[t2567.md\#](/intl.zh-CN/API参考/VPN网关/DescribeVpnConnection.md)|查询已创建的IPsec连接的详细信息。|
|[t2570.md\#](/intl.zh-CN/API参考/VPN网关/DownloadVpnConnectionConfig.md)|下载IPsec连接的配置信息。|
|[t2569.md\#](/intl.zh-CN/API参考/VPN网关/DeleteVpnConnection.md)|删除指定的IPsec连接。|

## SSL-VPN

|API|说明|
|---|--|
|[t2571.md\#](/intl.zh-CN/API参考/VPN网关/CreateSslVpnServer.md)|创建SSL-VPN服务端。|
|[t2574.md\#](/intl.zh-CN/API参考/VPN网关/ModifySslVpnServer.md)|修改SSL-VPN服务端的配置信息。|
|[t2572.md\#](/intl.zh-CN/API参考/VPN网关/DescribeSslVpnServers.md)|查询已创建的SSL-VPN服务端。|
|[t2573.md\#](/intl.zh-CN/API参考/VPN网关/DeleteSslVpnServer.md)|删除SSL-VPN服务端实例。|
|[t2575.md\#](/intl.zh-CN/API参考/VPN网关/CreateSslVpnClientCert.md)|创建SSL-VPN客户端证书。|
|[t2578.md\#](/intl.zh-CN/API参考/VPN网关/ModifySslVpnClientCert.md)|修改SSL-VPN客户端证书的名称。|
|[t2576.md\#](/intl.zh-CN/API参考/VPN网关/DescribeSslVpnClientCerts.md)|查询已创建的SSL-VPN客户端证书。|
|[DescribeVpnSslServerLogs](/intl.zh-CN/API参考/VPN网关/DescribeVpnSslServerLogs.md)|查询SSL服务端的日志。|
|[t2577.md\#](/intl.zh-CN/API参考/VPN网关/DeleteSslVpnClientCert.md)|删除SSL-VPN客户端证书。|

