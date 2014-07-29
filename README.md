[ANY] Donor Menu
============
This is basically designed so you can have a Donor Menu without the hassle, just put the VIP commands in donors.cfg.

**Put the commands going in "donors.cfg" in "admin_overrides.cfg" so only admins and donors can use it!**

**Donors.cfg:** 
```
"Donor Menu"
{
    "title"    "Menu Title"
    "type"     "list"
    "items"
    {
        "sm_example"	"Here's an informational item"
        "sm_example2"  	"This launches a client command when selected"
    }
}
```

##Plugin Dependencies

[Admin Overrides](https://wiki.alliedmods.net/Overriding_Command_Access_(SourceMod))

##CVars
sm_donormenu_version (Do Not Touch this!)

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

Put "sm_donors" in "configs/admin_overrides.cfg"

**Example:** admin_overrides.cfg
```
Overrides
{
	"command"//<--Put Command Here	"flag"//<--Put Admin Flag Here
	"sm_donor"  "a"
}
```

##Credits
This is a modified version of [HelpMenu v0.3](https://forums.alliedmods.net/showthread.php?t=72576)
