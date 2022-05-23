# Welcome to Sentinel!

Sentinel is a powerful, efficient and fully secure password managing Discord Bot! With password being stored as Cypher-text, sentinel assures a secure environment for your password storage.

## The Sentinel Environment
Sentinel provides a safe and secure environment even within any Discord server by creating a private channel for every user. The private channel can only be accessed by user and the bot. Feel free to add, retrieve and update your passwords in the channel.

## Commands

| S.no | Command | Description | Example |
| --- | --- | --- | --- |
| 1. | `>snew` | To start using sentinel, every user must have to run this command in #sentinel-main channel. This will initialise the bot and create a private channel for the user. | `>snew` |
| 2. | `>sadd` | This command will allow user to add the passwords. This command takes in 3 parameters: username, password and website. | `>sadd cypher compaq google.com` |
| 3. | `>sget` | This command will print all the passwords of a user in a beautiful tabular format. | `>sget` |
| 4. | `>delete` | This command will allow the user to delete his/her desired password. This command takes 2 parameters: username and website of the desired password to be deleted. | `>sdelete cypher google.com` |
| 5. | `>shelp` | Get all commands and important links. | `>shelp` |

## Security levels

1. All of the data is securely converted to **Cypher-text** and stored in a **secure environment**.
2. All the password is stored **registered with your unique discord ID** ensuring no one can access your passwords under any circumstances.
3. All commands can be run in a **private channels** allowing no one to see your messages with the bot.

## Installation

[**Click here**](https://discord.com/api/oauth2/authorize?client_id=922866629229039626&permissions=534723951696&scope=bot) to install Sentinel to your server.

The bot will ask set off permissions. [See all permissions here](https://github.com/sentinel-db/sentinel/blob/main/docs/permissions.md). Once approved, the bot will enter the server and create a new category named 'sentinel'. Under that category, it will create a new channel named 'sentinel-main'. Users can start running their commands and setup their private channels here.
