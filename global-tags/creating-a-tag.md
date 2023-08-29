---
description: >-
  Okay, so you've read about what tags are and understand what they are. Lets
  look into making them
---

# Tag Creation

## Creating a tag

There are two ways to create a tag. The first way is using old-fashioned text commands, and the second way is using slash commands. We will go over both.

### Creating a tag from a text command

`*tag create [name] [content]`

{% hint style="info" %}
By default name **cannot** take spaces. This means if you want the name to be `my test` and you were to run `*tag create my test` the tag name would be `my` and the content would be `test`.

To get around this, type the following: `*tag create "my test" my content`
{% endhint %}

<figure><img src="https://i.imgur.com/y2wekcs.png" alt=""><figcaption><p>An text command example on creating a tag</p></figcaption></figure>

### Creating a tag from a slash command

To create a tag from a slash command, use `/tag create`

![](https://i.imgur.com/z5M19qN.png) ![](https://i.imgur.com/N6JVcB2.png)

Unlike the text command, this doesn't require quotes to allow spaces in the name
