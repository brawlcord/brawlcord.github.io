<h1 align="center"><i> <a href=".">Main Page</a> // <a href="https://discord.com/oauth2/authorize?client_id=644118957917208576&scope=bot&permissions=322624&scope=bot">Invite Bot</a></i></h1>

While you can host an instance of Brawlcord yourself, please use [the public Brawlcord bot](https://discord.com/oauth2/authorize?client_id=644118957917208576&scope=bot&permissions=322624&scope=bot) unless you have a good reason to host it yourself.

**Important Note:** Brawlcord is getting rewritten as a standalone bot in a different programming language. The future versions of the bot will not be available as Red cogs. See [this](discontinuing-red.md) for more info.

**Note:** Brawlcord requires the `Members` priveleged intent to be enabled to work properly. The bot can work without it, but some commands may have limited functionality. Brawlcord does not require the `Presence` privileged intent to be enabled. However, Red Bot requires both the privileged intents to be enabled. It is not an issue for bots in less than 100 servers, however, it might be a concern for bots in more than 100 servers that do not have [intents whitelisted](https://support.discord.com/hc/en-us/articles/360040720412-Bot-Verification-and-Data-Whitelisting#privileged-intent-whitelisting). You may use [this fork](https://github.com/snowsee/Red-DiscordBot) of Red to run the bot without any privileged intents. More information about enabling intents can be found on the Red installation guide linked below.

First make sure you have Red Bot V3 installed. Instructions to install Red Bot can be found [here](https://github.com/Cog-Creators/Red-DiscordBot#installation).

Next add my repo using the following command:

> Note: [p] will be your prefix in all of the following commands.  

`[p]repo add brawlcord https://github.com/brawlcord/brawlcord-red`

Then, you will have to install cog by using the following command:

`[p]cog install brawlcord brawlcord`

You should see the following message after the installation:
> Thank you for installing the Brawlcord cog, based on the mobile game Brawl Stars (developed by Supercell).

Load the cog once you see that message using the following command:
`[p]load brawlcord`

Make sure that you use the `[p]cog update` command to periodically update your cogs. This will ensure that you are getting the latest bug fixes and features. You may also update a specific cog by using `[p]cog update brawlcord`.

**Important Note**: The cog uses external Brawl Stars emotes. They are stored in the following four Discord servers:

- [Brawlcord Community Server](https://discord.gg/7zJ3PbJ)
- [Brawlcord Emotes: SP 1](https://discord.gg/rxZaMmN)
- [Brawlcord Emotes: SP 2](https://discord.gg/HydSxwW)
- [Brawlcord Emotes: Ranks](https://discord.gg/5tT88HM)
- [Brawlcord Emotes: Brawlers and Game Modes](https://discord.gg/77Edmna)

Unfortunately, due to Discord limitations, you can't add your bot to these servers directly. In order to have your bot added to the abovementioned servers, you must send me a direct message with your bot's OAuth invite link. While I know this isn't ideal, this is currently the only working way. I'll work on adding an option to disable emotes in the future.  

My Discord username: **Snowsy#0592**
