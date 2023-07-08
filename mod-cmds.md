# Moderation Commands

## Description

Denonderbot support moderation commands that are used very frequently. 

> :warning: Moderation commands can only be performed to users who either have permissions to do the task or have a role that allows them to.

## Kick

The kick command simply kicks a user. Using the command: `!kick [user] [reason]`, administrators are able to kick a user from the server. You can either mention the specified user or enter their user ID.

Requirements: `kick_members`

![kick_members](images\kick_members.png)

## Ban

The ban command bans a user from the guild. Using the command: `!ban [user] [reason]`, the bot will ban a user. Banning a user removes them from the server and does not allow the user the join unless unbanned.

Requirements: `ban_members`

![ban_members](images\ban_members.png)

## Unban

The unban command does the opposite of the ban command. The syntax for this command is: `!unban [user]`. 

Requirements: `ban_members`

![ban_members](images\ban_members.png)