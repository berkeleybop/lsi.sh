# lsi.sh

This is a public repository for the lovely [wrapper script](https://calomel.org/megacli_lsi_commands.html) created by [Calomel.org](https://calomel.org/) for the LSI hardware RAID command line tool MegaCLI, [provided](https://calomel.org/calomel_at.html) Creative Commons Attribution-ShareAlike 4.0 International [license](http://creativecommons.org/licenses/by-sa/4.0/).

Their original description was simply:

```
Calomel.org 
    https://calomel.org/megacli_lsi_commands.html
    LSI MegaRaid CLI 
    lsi.sh @ Version 0.05

description: MegaCLI script to configure and monitor LSI raid cards.
```

Building on the shoulder of giants. I have added a little
"autoconfiguration", pathing for the default Ubuntu package, and a
couple small additions to their script to make dealing with an LSI
RAID system a little easier.

I'm hoping by putting this out there to encourage further development and extensions to try and bring `MegaCLI` under control.

# Environment

I'm working under an Ubuntu/Debian environment, but I think the only
real change that anybody on any \*nix would need make is in the
`MegaCli` variable at the top of the file.

To get a proper scriptable package for Ubuntu and deployments, I
followed the
instructions [here](http://hwraid.le-vert.net/wiki/DebianPackages),
from another very useful LSI
MegaRAID [resource](http://hwraid.le-vert.net/wiki/LSIMegaRAIDSAS).

An additional shout out to the useful RAID wiki on kernel.org for [their information](https://raid.wiki.kernel.org/index.php/Hardware_Raid_Setup_using_MegaCli) on MegaCli.

