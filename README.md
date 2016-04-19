# Casual-Dark: BetterDiscord theme

I don't recommend using my CSS as a way to learn. It's very disorganized, out of order, and very little comments.

![Preview](example.png) 

Requirements:

[BetterDiscord](https://betterdiscord.net/)

and

[BetterDiscord+](https://github.com/Bluscream/BetterDiscord-Plugins-and-Themes)

1. Add to C:\Users\NAME\AppData\Roaming\BetterDiscord\themes
2. Press CTRL+R to reload BetterDiscord
3. Enable in BetterDiscord > Themes in settings.

If you want the icon that shows up next to the server icons when there's new messages on that server:

1. CTRL+F
2. .guilds li .guild-inner:before {
3. Remove the line that says
4. display:none;
