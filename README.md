# Left 4 Dead Slots Forked

## Description ##

Forked from [L4D & L4D2] Left 4 Dead Slots made by Accelerator.<br>
https://forums.alliedmods.net/showthread.php?t=333092

add AutoExecConfig, basically.<br>
基本上是使其能夠自動設定 cvar，不然老是自動設成預設.

功能與 L4D2ToolZ 一樣.<br>
Cvars:
sv_maxplayers - max human players that can join your server. -1 to disable and use standart check (range 0 to 18 ).<br>
sv_removehumanlimit - remove kick for players (only L4D) when they are more than 8 for vs and 4 for coop(0 to disable, 1 to enable).<br>
sv_force_unreserved - if you set it to 1 before connection from lobby your server will stay unreserved and allow players to connect using connect command, this command sets.

## Requirements ##
- SourceMod 1.11.6696 and newer

- remove L4D2ToolZ plugins (if there is)
- 該插件不能與 L4D2ToolZ 共存

## Install ##

put l4dslots.smx into \addons\sourcemod\plugins\ folder.<br>
put l4dslots.txt into \addons\sourcemod\gamedata\ folder.
