SM-DonorMenu
============
This is basically designed so you can have a Donor Menu without the hassle, just put the VIP commands in donors.cfg.

**Put the commands going in "donors.cfg" in "admin_overrides.cfg" so only admins and donors can use it!**

**Donors.cfg:** 
```
"Donor"
{
	"<MenuName>"
	{
		"items"
		{
			"<sm_command>" "<Command Name>"
			"<sm_command2>" "<Example Name>"
		}
	}
}
```
*Modify the items in <> only!*

**Plugin Dependencies:**

[Admin Overrides](https://wiki.alliedmods.net/Overriding_Command_Access_(SourceMod))

**Recommended Addons:**

[SourceBans](https://forums.alliedmods.net/showthread.php?t=61000)

[SourceBans Donations Control](https://forums.alliedmods.net/showthread.php?t=221742)

##CVARS
sm_donormenu_version

##Commands
**Console:** sm_donor

**Chat:** !donor

##Changelog
- **0.3** - Modified code so it can work alongside HelpMenu
- **0.2** - Fixed Menu saying "Help Menu" rather than "Donor Menu"
- **0.1** - Initial Release

##How to Install
"donormenu.smx" --> "<game>/addons/sourcemod/plugins"

"donors.cfg" --> "<game>/addons/sourcemod/configs"

##Credits
This is a modified version of [HelpMenu v0.3](https://forums.alliedmods.net/showthread.php?t=72576)
