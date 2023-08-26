---
description: Learn how to start the counting channel.
cover: ../.gitbook/assets/countbotblack.png
coverY: 0
---

# Basic Setup

Once CountBot has been added to your server, a server member with `Administrator` permission may use `/config set-channel <channel>` to set the counting channel.

{% hint style="warning" %}
Please make sure that CountBot has the following permissions for all features to work properly:

```
ManageChannels
ReadMessageHistory
SendMessages
ViewChannel
ManageMessages
EmbedLinks
AddReactions
UseExternalEmojis
ManageRoles
```
{% endhint %}

Here are the default configurations. Read more about them [**here**](advanced.md).

| Setting              | Default Value |
| -------------------- | ------------- |
| Consecutive Counting | false         |
| Count Validation     | false         |
| Chatting             | false         |
| Sudden Death         | false         |
| Items                | true          |
