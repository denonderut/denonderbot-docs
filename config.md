# Config

## Logging Channel

Denonderbot logs events such as deleted messages, edited messages, new channels, edited channels, deleted channels, new roles, etc. Denonderbot will log to a specified channel that is set up by an administrator. To specify the logging channel, send `!logs_channel`. The bot will then wait for a reposnse in the form of a channel ID.


## Welcome Channel

Denonderbot will send an embed when a member joins the server. The channel you want these messages to be sent to can be specified with the command: `!welcome_channel`. You will be asked to enter a welcome channel ID. After this, your welcome channel will be set and messages by the bot will be sent.

## Goodbye Channel

Similar to the [Welcome Channel](config?id=welcome-channel), the bot will send a message when a user leaves the server. This can be set by running: `!goodbye_channel`. Again, you will enter a goodbye channel ID and the goodbye channel will be set.

## Help

### How do I get the channel ID?

To get the channel ID of a channel, right click on it and click "Copy Channel ID". You can now send this ID for the bot to read.

![Copy Channel ID](images\copy-channel-id.png) 