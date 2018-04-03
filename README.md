[![Discord](https://discordapp.com/api/guilds/414512153786187776/widget.png)](https://discord.gg/FAygeev)
[![Discord Bots](https://discordbots.org/api/widget/status/414512049679237122.svg?noavatar=true)](https://discordbots.org/bot/414512049679237122)

# Trident
A high-quality multi-purpose discord bot

# What is Trident?
Trident is a high quality, friendly, multi-purpose entertainment bot. With many features such as but not only meme images, image manipulation, moderation, and music! We support Youtube, Twitch, Soundcloud and more!

# Notable Features

* Music. Lag free music with the ability to play from many sources such as Youtube, Twitch, Soundcloud.
* Moderation. Easy to use moderation commands such as ban, softban, kick, purge and more.
* Image manipulation. The power to put an avatar/image on a template to create fantastic jokes with friends.
* Join/Leave Messages. Welcome your new members to your server with customizable welcome/leave messages.

# Prefix
The prefix is what tells the bot that your message is a command and not just any message. The default prefix is `t.`, Let's say we wanted to change the prefix to `t!` we can use the `prefix` command so `t.prefix t!` which will change the prefix to `t!`. The prefix in DM's is `t.`, you can set a custom prefix per guild. You can always trigger the bot by using a mention prefix: `@Trident#8422`.

# Usage
Usage is a template for how a command can be used. It is made up of [**Aliases**](#aliases) and [**Arguments**](#arguments).

# Aliases
Command aliases, It's exactly what it sounds like. Multiple names for one command that you can use to trigger the same command with different names that will produce the same result. They're wrapped in `《 》` and separated by `|`, like this: `《info|what|details》`. This means in a guild where the prefix is `t.` that command can be triggered as `t.info`, `t.what` or `t.details`.

# Arguments
Arguments are the additional pieces of information you provide, to get the information you are looking for. Arguments are separated into 2 categories, required and optional. Required arguments are wrapped in `< >`. Optional arguments are wrapped in `[ ]`. Arguments follow the following format `Name:Type{Min,Max}`.

Example: `<Points:int{1,50}> [Level:int{1,120}]`

  * Points is a required argument: it is expecting an integer type with a minimum value of 1 and maximum of 50.
  * Level is an optional argument: it is expecting an integer type with a minimum value of 1 and maximum of 120.

**Note: Min & Max may be omitted separately, or completely when the argument has no min or max.**

# Argument Types
Arguments expect certain types of data and are validated before the command is even run. For instance, if you provide a String (letters) where the bot is expecting a Number, that can be a problem if it isn't caught. Although, some arguments may accept multiple types like: `<ItemID:int|ItemName:str>`. That single argument can be an ItemID as an integer or an ItemName as a string.

The following types are available: 
  * **literal**: Literally matches the argument name. This is the default type if none is shown.
  * **boolean**: `true` or `false`
  * **float, num, number**: Any rational number, written as a decimal. Min/Max refers to the Value.
  * **int, integer**: Positive or Negative Whole Numbers. Min/Max refers to the Value.
  * **str, string**: Letters and or Letters and numbers mixed. Min/Max refers to the Character Length.
  * **url**: A valid URL/Link.
  * **channel**: A Discord channel id or mention.
  * **guild**: A Discord Guild ID.
  * **member**: A Mention or Discord User ID in the context of a guild.
  * **msg, message**: A Discord Message ID.
  * **role**: A Discord Role ID or role mention.
  * **user, mention**: A Discord User ID or user mention.
  * **duration**: Human formatted time like `15 minutes`
  * **channelname**: A channel id, channel name or channel mention
  * **guildname**: A guild id or name.
  * **membername**: A member username, nickname, id, user tag or mention.
  * **rolename**: A role id, mention or name.
  * **songname**: Used for resolving tracks in the play command.
  * **username**: A user id, tag, username or mention.

# Support Server
[![Discord](https://discordapp.com/api/guilds/414512153786187776/widget.png?style=banner2)](https://discord.gg/FAygeev)

# Other Links
[![Discord Bots](https://discordbots.org/api/widget/414512049679237122.svg)](https://discordbots.org/bot/414512049679237122)
