# Overview

You can label and classify VPN gateways by attaching tags to them. Using tags can help facilitate resource search and management.

## Features

![Classify VPN gateways by tag](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/en-US/2831420061/p147432.png)

As shown in the preceding figure, it is difficult to manage a large number of VPN gateways. You can use tags to group VPN gateways. This allows you to search and filter VPN gateways in a more efficient way.

A tag is a label that you can attach to a VPN gateway. Each tag is composed of a key-value pair. Before you use tags to manage VPN gateways, note that:

-   The keys of tags that are attached to the same VPN gateway must be unique.
-   Tags must be attached to VPN gateways.
-   Tag information is not shared across regions.

    For example, in the China \(Shanghai\) region, you cannot view tags of instances that are created in the China \(Hangzhou\) region.

-   You can modify the key and value of a tag, or remove the tag. If you delete a VPN gateway, all the tags that are attached to it are removed.

## Limits

You can attach up to 20 tags to each VPN gateway. You cannot increase the quota limit.

## Manage tags

The following table lists the operations that you can perform to manage tags.

|Operation|Console|API|
|---------|-------|---|
|Attach tags|[Attach tags to a VPN gateway]()|[TagResources](/intl.en-US/API reference/Tag/TagResources.md)|
|[Attach tags to multiple VPN gateways at a time]()|
|Search VPN gateways by tag|[Search VPN gateways by tag]()|[ListTagResources](/intl.en-US/API reference/Tag/ListTagResources.md)|
|Remove tags|[Remove tags from a VPN gateway]()|[UnTagResources](/intl.en-US/API reference/Tag/UnTagResources.md)|
|[Remove tags from multiple VPN gateways at a time]()|

