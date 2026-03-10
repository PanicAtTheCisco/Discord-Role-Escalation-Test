# Discord-Role-Escalation-Test
## Version: 1.4
A backdoored Discord bot with the capabilities of elevating a user's permissons on any Discord Server it is invited to. This was created as a learning project for JS and Discord bots

---
 ## REQUIREMENTS:
 * node.js installed
 * discord.js npm packaged installed

 ## HOW TO START:
 * Clone this repo
 * Create config.json for discord token (https://discordjs.guide/creating-your-bot/)
 * Setup bot as an application on your discord developer portal (https://discord.com/developers/applications)
 * Create invite link using Discord's built in link generator and make sure the bot's permissions are set to only administrator 
 * Add bot to server
 * Change to directory of bot in terminal
 * Run 'node .' in terminal to start bot
 
 ## NOTE:
 * I wrote part of this a while ago, so this is likely not using the latest discord.js
 * Bot must be on the server for use
 * There are still a few bugs being worked with the '-create' and '-add' commands so expect a few issues
 * There is no multi-command handling so if more than one person tries to use a command at the same time nothing will happen for either of them. If needed on multiple servers it is recommened to host different instances of the bot
 * This bot is meant to be used as a role escalation test for Discord servers
 * Bot can be customized to be used however is needed to maintain cover, the default is the 'Funny Bot' cover which includes some jokes and other commands; customizing requires some discord.js knowledge
 * Commands can be added and removed for modularity, again, some discord.js knowledge is needed

---
# Change Log

## v1.4 Changes
* Switched joke command from using hardcoded jokes to using the icanhasdadjoke api to generate jokes

## v1.3 Changes
* Fixed security issues detected by GitHub Dependabot
* Made '-create' and '-add' commands automatically delete themselves in chat after execution to cover tracks
* Added comments with information regarding different functionality
* Created config.json requirement to prevent Discord Token from leaking
* Finally posted this project to GitHub
