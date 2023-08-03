---
description: The purge command uses a powerful flag-like syntax
---

# Purge

The syntax is as follows:\
\
`*purge amount -flags`

{% hint style="warning" %}
This command is useful for moderators, but be careful as it'll very quickly wipe messages you may not intended to wipe
{% endhint %}

To counter this, there are several **flags** you can use to help purge more efficiently

### Available Flags:

\[after/a]- Purge x messages AFTER the selected message

\[before/b] - Purge x messages BEFORE the selected message

\[bots/bot] - Purge x messages SENT by bots

\[webhooks/webhook/hooks] - Purge x messages SENT by webhooks

\[me] - Purge x messages SENT by The Manager

### Examples With Flags

`*purge 10 -a 1234567890` Purge 10 messages after the message with ID `1234567890`

`*purge 10 -b 1234567890` Purge 10 messages before the message with ID `1234567890`\
`*purge 10 -bot` - Purges 10 bot messages

`*purge 10 -hooks`- Purges 10 webhook messages

`*purge 10 -me` - Purges 10 of The Manager's messages
