# 📋 SparkyBot Command Reference

All commands are sorted by the permission level required to run them.

- 🔐 **Bot Owner Only** – Commands restricted to the bot owner
- 🛡️ **Administrator** – Server administrator commands
- ⚙️ **Manage Server** – Manage Guild permissions
- 📺 **Manage Channels** – Manage Channels permissions
- 🔨 **Kick / Ban Members** – Kick and Ban permissions
- ⏱️ **Moderate Members** – Timeout permissions
- 📝 **Manage Messages** – Manage Messages permissions
- 🎭 **Manage Roles** – Manage Roles permissions
- ✏️ **Manage Nicknames** – Manage Nicknames permissions
- 🌍 **@everyone** – No special permissions required

---

## 🔐 Bot Owner Only

| Command | Description |
|---------|-------------|
| `/owner setlog` | Set owner log channel |
| `/owner removelog` | Remove owner log channel |
| `/owner checklog` | Check owner log status |
| `/owner listservers` | List all servers the bot is in |
| `/owner reload` | Reload a cog |
| `/owner restart` | Restart the bot |
| `/owner shutdown` | Shut down the bot |
| `/owner globalannounce` | Send announcement to all servers |
| `/owner leaveserver` | Make the bot leave a server |
| `/owner serverstats` | View bot-wide statistics |
| `/owner globalpoll` | Create a global poll |
| `/owner pollclose` | Close a global poll early |
| `/owner pollresults` | View poll results |
| `/owner pollban` | Ban a user from a poll |
| `/owner pollunban` | Unban a user from a poll |
| `/owner polldelete` | Delete a global poll |
| `/owner polllist` | List all global polls |
| `/owner 247approve` | Approve 24/7 mode for a server |
| `/owner 247unapprove` | Remove 24/7 approval |
| `/owner 247list` | List approved 24/7 servers |

---

## 🛡️ Administrator

| Command | Description |
|---------|-------------|
| `/admin reset` | Reset a module's settings |
| `/mod jail` | Jail a member |
| `/mod unjail` | Unjail a member |
| `/mod setjailrole` | Set the jail role |
| `/mod setlog` | Set moderation log channel |
| `/tkt manage add` | Add a ticket category |
| `/tkt manage remove` | Remove a ticket category |
| `/tkt manage reset` | Reset categories to defaults |
| `/tkt manage cat` | Set ticket category name |
| `/tkt manage time` | Set staff support hours |
| `/tkt manage rmtime` | Remove support hours |
| `/tkt manage embed` | Set custom ticket embed |
| `/tkt fields add` | Add a form field |
| `/tkt fields remove` | Remove a form field |
| `/tkt staff type` | Add/remove type staff role |
| `/tkt staff global` | Add/remove global staff role |
| `/tkt customize menu` | Customize ticket panel |
| `/antinuke enable` | Enable anti-nuke |
| `/antinuke disable` | Disable anti-nuke |
| `/antinuke punishment` | Set default punishment |
| `/antinuke setlog` | Set anti-nuke log channel |
| `/antinuke eventconfig` | Configure event settings |
| `/antinuke whitelist` | Whitelist a user |
| `/antinuke whitelistrole` | Whitelist a role |
| `/antinuke forbidchannel` | Forbid a channel |
| `/antinuke forbidcategory` | Forbid a category |
| `/antinuke clearviolations` | Clear violations |
| `/logging setchannel` | Set logging channel |
| `/logging config` | Toggle log events |
| `/logging toggle` | Enable/disable logging |
| `/forumlock set` | Set forum auto-lock |
| `/forumlock setlog` | Set forum lock log |
| `/forumlock remove` | Remove forum lock |
| `/forumlock toggle` | Toggle forum lock |
| `/forumlock update` | Update forum lock duration |
| `/verify setup` | Setup verification system |
| `/verify panel` | Post verification panel |
| `/verify reset` | Reset verification data |
| `/verify cleanup` | Clean up verification channels |
| `/application create` | Create an application |
| `/application delete` | Delete an application |
| `/eco setrolerole` | Configure role shop item |
| `/eco removeroleitem` | Disable a role item |
| `/eco roleitemsconfig` | View role item config |
| `/eco removeroleitemsall` | Clear all role items |
| `/lv setchannel` | Set level-up channel |
| `/lv rstchannel` | Reset level-up channel |
| `/lv setxp` | Set a user's XP |
| `/lv role` | Add level reward role |
| `/lv rmrole` | Remove level reward role |
| `/lv bl` | Block channel from XP |
| `/lv toggle` | Enable/disable leveling |
| `/lv text` | Set custom level-up message text |
| `/am status` | View AutoMod config |
| `/am toggle` | Enable/disable AutoMod |
| `/am spam` | Toggle anti-spam |
| `/am invite` | Toggle anti-invite |
| `/am links` | Toggle anti-links |
| `/am caps` | Toggle caps filter |
| `/am mentions` | Set mention limit |
| `/am addword` | Add bad word |
| `/am delword` | Remove bad word |
| `/am log` | Set AutoMod log channel |
| `/am ignorech` | Globally ignore a channel |
| `/am ignorerole` | Globally ignore a role |
| `/am wlu` | Module whitelist user |
| `/am wlr` | Module whitelist role |
| `/am wlc` | Module whitelist channel |
| `/am wlcat` | Module whitelist category |
| `/am wllist` | List module whitelists |
| `/am wlclear` | Clear module whitelist |
| `/jtc setup` | Set up JTC system |
| `/jtc name` | Set JTC name template |
| `/jtc limit` | Set JTC default limit |
| `/jtc panel` | Refresh JTC control panel |
| `/invites reset` | Reset a member's invites |
| `/invites resetall` | Reset all invite data |
| `/messages reset` | Reset message stats |
| `/rules delete` | Delete a rules panel |
| `/music vc` | Set designated music VC |
| `/music removevc` | Remove music VC |
| `/music vcinfo` | View music VC config |
| `/music status` | Toggle VC status updates |
| `/music panel` | Send music control panel |
| `/music removepanel` | Remove music panel |
| `/music 247` | Enable/disable 24/7 mode |
| `/music 247status` | Check 24/7 status |
| `/rp set` | Set report channel |
| `/rp setsug` | Set suggestion channel |
| `/rp setbug` | Set bug report channel |
| `/autotranslate enable` | Enable auto-translate |
| `/autotranslate disable` | Disable auto-translate |
| `/autotranslate setlanguage` | Set default language |
| `/autotranslate ignorechannel` | Ignore channel |
| `/autotranslate unignorechannel` | Unignore channel |
| `/autotranslate ignorerole` | Ignore role |
| `/autotranslate unignorerole` | Unignore role |
| `/autotranslate ignoreuser` | Ignore user |
| `/autotranslate unignoreuser` | Unignore user |
| `/counting setsavecooldown` | Set cooldown for counting saves |

---

## ⚙️ Manage Server

| Command | Description |
|---------|-------------|
| `/mod clearwarns` | Clear a member's warnings |
| `/mod jaillist` | List jailed members |
| `/gwy start` | Start a giveaway |
| `/gwy end` | End a giveaway |
| `/gwy reroll` | Reroll giveaway winners |
| `/gwy list` | List active giveaways |
| `/gwy edit` | Edit a giveaway |
| `/gwy info` | View giveaway details |
| `/wel set` | Set welcome channel |
| `/wel setgoodbye` | Set goodbye channel |
| `/wel config` | Configure welcome message |
| `/wel goodbyeconfig` | Configure goodbye message |
| `/wel setmsg` | Set welcome message |
| `/wel setgoodbyemsg` | Set goodbye message |
| `/wel setdm` | Set welcome DM |
| `/wel toggleembed` | Toggle embed mode |
| `/wel preview` | Preview welcome/goodbye |
| `/youtube add` | Track a YouTube channel |
| `/youtube remove` | Stop tracking a channel |
| `/youtube list` | List tracked channels |
| `/youtube addfilter` | Add keyword filter |
| `/youtube removefilter` | Remove keyword filter |
| `/youtube clearfilters` | Clear all filters |
| `/youtube filters` | View active filters |
| `/youtube setmessage` | Set custom notification message |
| `/youtube setchannel` | Change notification channel |
| `/lv status` | Check leveling system status |
| `/prefix set` | Set the bot's prefix |
| `/prefix add` | Add an additional prefix |
| `/prefix remove` | Remove a prefix |
| `/prefix reset` | Reset prefixes to default |
| `/prefix list` | List all server prefixes |
| `/antinuke status` | View anti-nuke status |
| `/antinuke eventlist` | List event configs |
| `/antinuke whitelistinfo` | View user whitelist status |
| `/antinuke whitelistroleinfo` | View role whitelist status |
| `/antinuke whitelistroles` | List whitelisted roles |
| `/antinuke violations` | View user violations |
| `/rp suglist` | List pending suggestions |
| `/application list` | List all applications |
| `/application open` | Open an application |
| `/application close` | Close an application |
| `/application setlogchannel` | Set app log channel |
| `/application setrole` | Set grant role |
| `/application setcooldown` | Set application cooldown |
| `/application resetcooldown` | Reset a user's cooldown |
| `/application checkstatus` | Check user's status |
| `/application post` | Post an apply button |
| `/application postmulti` | Post multi-application panel |
| `/application manager` | Set manager roles |
| `/application preview` | Preview application |
| `/rules create` | Create rules panel |
| `/rules additem` | Add rule item |
| `/rules edititem` | Edit rule item |
| `/rules removeitem` | Remove rule item |
| `/rules preview` | Preview rules panel |
| `/rules list` | List rules panels |
| `/rules post` | Post rules panel |
| `/forumlock list` | List forum lock settings |
| `/autotranslate status` | View auto-translate config |
| `/invites setlogchannel` | Set invite log channel |

---

## 📺 Manage Channels

| Command | Description |
|---------|-------------|
| `/mod lock` | Lock a channel |
| `/mod unlock` | Unlock a channel |
| `/mod slowmode` | Set channel slowmode |
| `/tkt manage listcats` | List ticket categories |
| `/tkt manage clean` | Clean stale ticket records |
| `/tkt manage count` | Show open ticket count |
| `/tkt manage list` | List open tickets |
| `/tkt manage reviews` | View ticket reviews |
| `/tkt adduser` | Add user to ticket |
| `/tkt removeuser` | Remove user from ticket |
| `/tkt open` | Manually open a ticket |
| `/tkt close` | Close a ticket |
| `/tkt closereq` | Request ticket closure |
| `/tkt autoclose` | Set auto-close timer |
| `/tkt rmautoclose` | Remove auto-close timer |
| `/tkt transcript` | Generate ticket transcript |
| `/tkt staff info` | View staff config |
| `/admin channeldelay` | Set slowmode via admin |
| `/jtc info` | View JTC configuration |

---

## 🔨 Kick / Ban Members

| Command | Description |
|---------|-------------|
| `/mod kick` | Kick a member |
| `/mod ban` | Ban a member |
| `/mod unban` | Unban a user by ID |

---

## ⏱️ Moderate Members (Timeout)

| Command | Description |
|---------|-------------|
| `/mod mute` | Timeout a member |
| `/mod unmute` | Remove timeout |

---

## 📝 Manage Messages

| Command | Description |
|---------|-------------|
| `/mod warn` | Warn a member |
| `/mod warnings` | View warnings |
| `/mod purge` | Bulk-delete messages |
| `/embed send` | Send embed via modal |
| `/embed quick` | Send quick embed |
| `/embed edit` | Edit an existing embed |
| `/embed addfield` | Add field to embed |
| `/embed clearfields` | Clear all embed fields |
| `/embed setauthor` | Set embed author |
| `/embed json` | Send embed from JSON |
| `/embed preview` | Preview an embed |
| `/verify status` | Check verification status |
| `/verify user` | Manually verify a user |
| `/verify unverify` | Unverify a user |
| `/rp list` | View pending reports |

---

## 🎭 Manage Roles

| Command | Description |
|---------|-------------|
| `/mod role` | Add/remove a role |
| `/wel autorole` | Add/remove auto-role |
| `/wel listautoroles` | List auto-roles |
| `/rr add` | Add reaction role |
| `/rr remove` | Remove reaction role |
| `/rr list` | List reaction roles |
| `/rr clear` | Clear reaction roles from a message |
| `/rr panel` | Create reaction role panel |

---

## ✏️ Manage Nicknames

| Command | Description |
|---------|-------------|
| `/mod nick` | Change a member's nickname |
| `/admin botnick` | Change the bot's nickname |

---

## 🌍 @everyone

### Economy Commands
| Command | Description |
|---------|-------------|
| `/eco bal` | Check balance |
| `/eco daily` | Claim daily reward |
| `/eco work` | Work your job |
| `/eco job` | View or choose a job |
| `/eco resign` | Resign from your job |
| `/eco pay` | Pay another user |
| `/eco dep` | Deposit to bank |
| `/eco with` | Withdraw from bank |
| `/eco rob` | Rob another user |
| `/eco gamble` | Gamble your coins |
| `/eco slots` | Play slots |
| `/eco shop` | View the shop |
| `/eco buy` | Buy an item |
| `/eco inv` | View your inventory |
| `/eco use` | Use an item |
| `/eco rich` | View richest members |

### Leveling Commands
| Command | Description |
|---------|-------------|
| `/lv rank` | View your rank |
| `/lv lb` | View leaderboard |
| `/lv roles` | List level reward roles |

### Fun Commands
| Command | Description |
|---------|-------------|
| `/fun 8ball` | Magic 8-ball |
| `/fun coinflip` | Flip a coin |
| `/fun dice` | Roll dice |
| `/fun rps` | Rock Paper Scissors |
| `/fun choose` | Choose an option |
| `/fun reverse` | Reverse text |
| `/fun mock` | Mock text |
| `/fun emojify` | Convert text to emojis |
| `/fun rate` | Rate something |
| `/fun fact` | Random fact |
| `/fun roast` | Roast a user |
| `/fun compliment` | Send a compliment |
| `/fun ship` | Ship two users |
| `/fun trivia` | Play trivia |

### Utility Commands
| Command | Description |
|---------|-------------|
| `/utility help` | Open the help menu |
| `/utility ping` | Check bot latency |
| `/utility userinfo` | View user info |
| `/utility serverinfo` | View server info |
| `/utility avatar` | View avatar |
| `/utility banner` | View banner |
| `/utility roleinfo` | View role info |
| `/utility channelinfo` | View channel info |
| `/utility invite` | Get bot invite link |
| `/utility poll` | Create a poll |
| `/utility remind` | Set a reminder |
| `/utility afk` | Set AFK status |
| `/utility timestamp` | Generate timestamp |
| `/utility emojis` | List server emojis |
| `/utility membercount` | View member count |

### Music Commands
| Command | Description |
|---------|-------------|
| `/music play` | Play a song |
| `/music pause` | Pause playback |
| `/music resume` | Resume playback |
| `/music skip` | Skip current song |
| `/music stop` | Stop and clear queue |
| `/music queue` | View queue |
| `/music nowplaying` | Show current song |
| `/music disconnect` | Leave voice channel |
| `/music shuffle` | Shuffle queue |
| `/music unshuffle` | Restore queue order |
| `/music loop` | Set loop mode |
| `/music remove` | Remove a song from queue |
| `/music clear` | Clear queue |
| `/music volume` | Adjust volume |
| `/music lyrics` | Fetch lyrics |
| `/music livelyrics` | Live synced lyrics |

### Translation Commands
| Command | Description |
|---------|-------------|
| `/translate text` | Translate text |
| `/translate detect` | Detect language |
| `/translate list` | List supported languages |
| `/transliterate text` | Transliterate text |
| `/transliterate scripts` | List transliteration scripts |

### Application Commands
| Command | Description |
|---------|-------------|
| `/application apply` | Apply for an application |

### Reports & Suggestions
| Command | Description |
|---------|-------------|
| `/rp report` | Report a member |
| `/rp suggest` | Submit a suggestion |
| `/rp bug` | Report a bug |

### Invite Tracking
| Command | Description |
|---------|-------------|
| `/invites check` | Check your invites |
| `/invites leaderboard` | View invite leaderboard |
| `/invites info` | Look up invite code |
| `/invites members` | List invited members |

### Message Statistics
| Command | Description |
|---------|-------------|
| `/messages stats` | View message stats |
| `/messages leaderboard` | Message leaderboard |
| `/messages serverstats` | Server message stats |

### Counting
| Command | Description |
|---------|-------------|
| `/counting mystats` | Your counting stats |

### Ticket System
| Command | Description |
|---------|-------------|
| `/tkt history` | View your ticket history |

### JTC (Join-to-Create)
| Command | Description |
|---------|-------------|
| `/jtc lock` | Lock your JTC channel |
| `/jtc unlock` | Unlock your JTC channel |
| `/jtc hide` | Hide your JTC channel |
| `/jtc unhide` | Unhide your JTC channel |
| `/jtc allow_role` | Allow role into JTC |
| `/jtc allow_user` | Allow user into JTC |
| `/jtc kick_user` | Kick user from JTC |
| `/jtc transfer` | Transfer JTC ownership |
| `/jtc region` | Change JTC region |
| `/jtc limit` | Set JTC user limit |
| `/jtc bitrate` | Set JTC bitrate |
| `/jtc rename` | Rename your JTC channel |

---

**Prefix Version:** Most commands also have prefix equivalents using the default `//` prefix (e.g., `//help`, `//ping`). Check the bot's help menu for the full list.
