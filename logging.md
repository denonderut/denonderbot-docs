# Logging

> :information_source: Please refer to the [Config](config.md) to set a logging channel.

## Description

Denonderbot will send a message to a specified channel when certain events take place. These events mostly include adding, removing, or editing messages or parts of a server.

## Events List

| Event | Description |
| ----- | ----------- |
| on_message_delete | Message deleted by a user. |
| on_message_edit | Message edited by a user. |
| on_guild_channel_create | Channel created. |
| on_guild_channel_delete | Channel deleted. |
| on_guild_channel_edit | Channel properties edited. |
| on_guild_role_create | Role created. |
| on_guild_role_delete | Role deleted. |
| on_guild_role_update | Role properties edited. | 
| on_member_join | Member joins the server. |
| on_member_remove | Member leaves the server. | 
| on_member_ban | Member banned from the server. |
| on_member_unban | Member unbanned from the server. |
| on_member_update | Server profile updated. |
| on_invite_create | Server invite created. | 