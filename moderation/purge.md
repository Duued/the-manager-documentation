---
description: >-
  The purge command uses subcommands to identify which type of purge you would
  like.
---

# Purge



The slash command uses `/purge messages` as the equivalent of the `*purge` command

{% hint style="info" %}
This duals as a slash command group and a text command group.
{% endhint %}

## Command syntax

&#x20;`*purge [subcommand] amount`

{% hint style="warning" %}
This command is useful for moderators, but be careful as it'll very quickly wipe messages you may not intended to wipe
{% endhint %}

To counter this, there are several **flags** you can use to help purge more efficiently

### Available Subcommands:

\[after/a]- Purge x messages AFTER the selected message

\[before/b] - Purge x messages BEFORE the selected message

\[bots/bot] - Purge x messages SENT by bots

\[webhooks/webhook/hooks] - Purge x messages SENT by webhooks

\[me] - Purge x messages SENT by The Manager

### Examples With Flags

`*purge a 10 1234567890` Purge 10 messages after the message with ID `1234567890`

`*purge before 10  1234567890` Purge 10 messages before the message with ID `1234567890`\
`*purge bot 10`- Purges 10 bot messages

`*purge 12 -hooks`- Purges 12 webhook messages

`*purge 15 -me` - Purges 15 of The Manager's messages
