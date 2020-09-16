# Attach tags to a VPN gateway

After you attach tags to VPN gateways, you can search and filter the VPN gateways by tag. This topic describes how to attach tags to a VPN gateway.

You can attach up to 20 tags to each VPN gateway. Before you start, note that:

-   The keys of tags that are attached to the same VPN gateway must be unique.
-   Tags must be attached to VPN gateways.
-   Tag information is not shared across regions.

    For example, in the China \(Shanghai\) region, you cannot view tags of instances that are created in the China \(Hangzhou\) region.

-   You can modify the key and value of a tag, or remove the tag. If you delete a VPN gateway, all the tags that are attached to it are removed.

1.  Log on to the [VPN gateway console](https://vpc.console.aliyun.com/vpn).

2.  In the top navigation bar, select the region where the VPN gateway is deployed.

3.  On the **VPN Gateways** page, find the VPN gateway to which you want to attach tags, move the pointer over the ![The Tag icon](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/en-US/8508559951/p67422.png) icon in the **Tags** column, and click **Add** in the message that appears.

4.  In the **Configure Tags** dialog box, set the following parameters, and click **OK**.

    |Parameter|Description|
    |---------|-----------|
    |**Tag Key**|You can select or enter a tag key. The tag key must be 1 to 64 characters in length and cannot start with `aliyun` or `acs:`. It cannot contain `http://` or `https://`. |
    |**Tag Value**|You can select or enter a tag value. The tag value must be 1 to 128 characters in length and cannot start with `aliyun` or `acs:`. It cannot contain `http://` or `https://`. |


**Related topics**  


[TagResources](/intl.en-US/API reference/Tag/TagResources.md)

