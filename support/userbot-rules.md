## Rules for user bots

```
Last edit:      01. October 2017 (relocated 16.01.2018)
Contributors: 	Skillkiller, Argex, zekro
```

1. The bot must have `-stop` command available for every **admin** and **owner** to shut down the bot in emergency.
	1.1 The stop command must be **exactly** assambled like this: `[perfix of the bot]stop` (ignore "[]")

2. The main administrative functions have to be available for every **staff member** *(moderator, supporter, admin ...)* on this guild.

3. The bot is not allowed to give normal members higher rights than the zekroBot / knechtBot and normal discord role settings does.

4. The prefix of the bot must be listed in knechtBot's prefix list *(see command `-prefix`)*.

5. The bot should not send unnecessary or annoying messages (spamming) and error / information messages should be deleted after time *(defaultly around 4 - 6 seconds)* in best case.

6. Bot Owners have to do follow every instruction of staff members in every case, unnecessary and independent from the reason.

7. Every bot is commited to write a bot log, in best case also a command log wich must be available for at least 4 weaks.
	7.1 The staff team will have full access at every time on the full log files and settings files also without given reason
  
8. The staff team can request code parts of the bot and the bot owner has to submit them on demand
	8.1 The team has only access in this case on code parts wich will change things or have access to the guild and guild information
  
9. Violation of that rules will lead to a kick or ban of the bot and also probably in some harder cases for the owner of the bot without giving a special reason for it.
  
Notice:
- The expanding of bot permissions is only allowed to **admins** *(or higher)* and the bot owner need to give senseful reasons for that. Also it's possible in some cases that the permissions of the bot needs to be expanded or suited individually.
- The names of the roles `Moderator`, `Supporter` and `Admin` will not be changed in the next time, so you can hardcode them, but i'ts recommended to softcode them in an external file, in best case with role ID's and not only the names (prevent abusement).

----

## @UserBot role permissions list

```
CREATE_INSTANT_INVITE    (Create Instant Invite)
MESSAGE_ADD_REACTION     (Add Reactions)
VIEW_CHANNEL             (Read Text Channels & See Voice Channels)
MESSAGE_READ             (Read Messages)
MESSAGE_WRITE            (Send Messages)
MESSAGE_MANAGE           (Manage Messages)
MESSAGE_EMBED_LINKS      (Embed Links)
MESSAGE_ATTACH_FILES     (Attach Files)
MESSAGE_HISTORY          (Read History)
MESSAGE_MENTION_EVERYONE (Mention Everyone) 
MESSAGE_EXT_EMOJI        (Use External Emojis)
VOICE_CONNECT            (Connect)
VOICE_SPEAK              (Speak)
VOICE_USE_VAD            (Use Voice Activity)
NICKNAME_CHANGE          (Change Nickname)
```