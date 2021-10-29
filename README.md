**📢 All about adding custom emojis to Discord Roles is here!**

⭐ _You can easily execute the steps with an eval command._

**Discord.js** actually has that functionality built-in with the **`GuildEmojiRoleManager`** class. The default collection is empty, making every emote accessible to every role. However, you can change that using the **`.add(), .remove(), and .set()`** methods.

Here's how you can use it for your command;

**```message.guild.emojis.cache.get('<Emote ID>') // first, get the emoji
   .roles // then the current role restrictions (default: none)
   .add(['<Role ID>', '<Role ID>'); // then add, set, or remove the specified roles```**



