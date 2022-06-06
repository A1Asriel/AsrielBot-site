# AsrielBot

AsrielBot is a friendly Discord bot which is mainly designed to solve ambiguity during the role-playing process. Although, it also can be used as a general purpose (moderation, custom responses, AFK statuses, etc.) bot.

Currently, it is in alpha development stage, so there will be more features and improvements over time!  
*It is planned to open the source code after we get to the full release.*


## Quick start

1. Invite the bot using the link above. It already has recommended permissions enabled for the proper operation.
2. Send `a!help` to see the list of all available commands.


## Features

### Role-playing commands

The bot can help players and game masters to decide whether a certain action was successful or not. *Try* it yourself by using `a!try` or `a!try3` command to determine if your character succeed in lifting up that heavy branch!

In the complex and huge RP servers it is often hard to trace the movements of the characters. They go back and forth, from location to location... But the `a!travel` command brings the players an easy and convenient way to mark that their characters were relocated to another channel, and the spectators will be able to follow them in a single click.

### Moderation

With this bot, you can set up a log channel which will trace every deleted or edited message, as well as mass deletion by other bots *(it won't recover the contents, unfortunately)*. Speaking of which, AsrielBot provides you a more convenient way of purging channels by simply marking the upper and lower messages, and it will delete every message in between. No more accidental deletion of extra messages by messing up with the numbers!

### User statuses

Every member of a server can mark themselves as AFK, busy or even sleeping without typing any commands! You just have to put `!afk`/`!away`, `!busy`/`!dnd` or `!sleep` into your status (it doesn't matter where exactly you are putting it). After that, every person who tries to ping you gets notified about your current unavailability.

### Multilingual

The bot can speak English, Russian and German (maintained by Zero). The admins should use `a!settings lang <language code>` to change it.  
We are open for the new contributors who are willing to bring their language into our project!
