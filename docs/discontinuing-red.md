<h1 align="center"><i> <a href=".">Main Page</a> // <a href="https://discord.com/oauth2/authorize?client_id=644118957917208576&scope=bot&permissions=322624&scope=bot">Invite Bot</a></i></h1>

Brawlcord is getting rewritten as a standalone bot in a different programming language. The future versions of the bot will not be available as Red cogs. While Red cogs are easier to set up, they don't give enough room for customization and optimization. Creating a standalone bot will resolve these issues.

If you use the [public Brawlcord bot](https://discord.com/oauth2/authorize?client_id=644118957917208576&scope=bot&permissions=322624&scope=bot), this does not affect you. However, if you host your own version of Brawlcord, please read the following.

Brawlcord's Red cog GitHub repo has changed from `brawlcord/brawlcord` to `brawlcord/brawlcord-red`. You need to update the repo's URL in your bot before **October 19, 2020**. Your bot may continue to work after that even if you don't update the URL, but it can break  anytime. To update the URL, follow these steps:

> **Note 1:** [p] will be your prefix in all of the following commands.  
> **Note 2:** In `repo` commands, replace `brawlcord` with the name of repo you chose when adding Brawlcord. If you're unsure, use `[p]repo list` command.

*Unload cog*  
`[p]unload brawlcord`

*Uninstall cog*  
`[p]cog uninstall brawlcord`

*Delete repo*  
`[p]repo delete brawlcord`

*Add new repo*  
`[p]repo add brawlcord https://github.com/brawlcord/brawlcord-red`

*Install cog*  
`[p]cog install brawlcord brawlcord`

*Load cog*  
`[p]load brawlcord`

Using these commands WILL preserve the previous data. Note that the cog will not get updates anymore. It may stop working due to a breaking change on Red. It supports a maximum of Red v3.4.
