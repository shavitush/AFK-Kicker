# AFK-Kicker
Kicks AFK players after verifying they're actually AFK.  
If the player doesn't do anything difference within X seconds, he will be prompted with a captcha-like random menu. Every menu option except for one ('Don't kick me!'), will kick the player as he was verified as a bot/AFK. He will also be kicked if he chooses nothing within Y seconds.  
Durations (X/Y) are definable. Check `cfg/sourcemod/plugin.afk_kicker.cfg` for CVars.

# Note
This plugin is for servers with rounds, such as casual and jailbreak servers.  
The plugin will most likely not function properly in MG/KZ/bhop/deathmatch!
