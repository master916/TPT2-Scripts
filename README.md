# TPT2-Scripts
Scripts for The Perfect Tower 2

Almost all of these scripts require 1920 x 1080 resolution with Dynamic UI Scaling turned on. Updated scripts to now check resolution before starting.


**Auto_Mine**

**Set up required**: Allocate perks for mining. Go to second floor of mine(you don't have to stay there just can't leave on lower floor), have infinity stone perk window open within the stone page. 

Description: Opens up the mine page which activates Auto_Mine_Layers and Drill scripts, waits for drill to finish then leaves the mine to go to the infinity stone page where it activates the earth stone and then it repeats. Turn off by pressing 9 to activate the off script. 

**Impulse: M**

```CUF1dG9fbWluZQEAAAAFa2V5Lm0BAAAAD2NvbXBhcmlzb24uYm9vbA5jb21wYXJpc29uLmludA1zY3JlZW4uaGVpZ2h0CGNvbnN0YW50BAI9PQhjb25zdGFudAI4BAAACGNvbnN0YW50BAEmDmNvbXBhcmlzb24uaW50DHNjcmVlbi53aWR0aAhjb25zdGFudAQCPT0IY29uc3RhbnQCgAcAAAgAAAAQdG93bi53aW5kb3cuc2hvdwhjb25zdGFudAQEbWluZQhjb25zdGFudAEBEWdlbmVyaWMud2FpdHVudGlsDmNvbXBhcmlzb24uaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAVsYXllcghjb25zdGFudAQCPT0IY29uc3RhbnQCDQAAABB0b3duLndpbmRvdy5zaG93CGNvbnN0YW50BARtaW5lCGNvbnN0YW50AQAMZ2VuZXJpYy53YWl0CGNvbnN0YW50A5qZmZmZmbk/DWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAACInUAIY29uc3RhbnQDAAAAAAA4g0ANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAACCcQAhjb25zdGFudAMAAAAAAKiLQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAnJ1ACGNvbnN0YW50AwAAAAAAfJBADGdlbmVyaWMuZ290bwhjb25zdGFudAIBAAAA```


**Auto_Mine_Layers**

No resolution restriction for this one

Description: Activates when the Mine is opened starts Drill script for each mine array position then opens new layer on each tab until they are all clear. Cleaning turns itself off when you leave the mine as well as unsets the glabal variable for the Drill script. (11-7-21 fixed error where is skipped orange...)

**Impulse: Open Mine**

```EEF1dG9fTWluZV9sYXllcnMBAAAACW9wZW4ubWluZQAAAAALAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BAVsYXllcghjb25zdGFudAL/////Dmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BApkcmlsbGFycmF5CGNvbnN0YW50AgAAAAAPZ2VuZXJpYy5leGVjdXRlCGNvbnN0YW50BAVEcmlsbBFnZW5lcmljLndhaXR1bnRpbA5jb21wYXJpc29uLmludA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQKZHJpbGxhcnJheQhjb25zdGFudAQCPT0IY29uc3RhbnQCEAAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQFbGF5ZXIOYXJpdGhtZXRpYy5pbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyCGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAAIbWluZS50YWIOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyDW1pbmUubmV3bGF5ZXIMZ2VuZXJpYy5nb3RvC3Rlcm5hcnkuaW50Dm1pbmUuaGFzTGF5ZXJzCGNvbnN0YW50AgcAAAALdGVybmFyeS5pbnQOY29tcGFyaXNvbi5pbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyCGNvbnN0YW50BAE8CGNvbnN0YW50Ag0AAAAIY29uc3RhbnQCBQAAAAhjb25zdGFudAIJAAAADGdlbmVyaWMuc3RvcAhjb25zdGFudAQFRHJpbGwMZ2xvYmFsLnVuc2V0CGNvbnN0YW50BAVMYXllcgxnbG9iYWwudW5zZXQIY29uc3RhbnQECkRyaWxsYXJyYXk=```

**Drill**

No resolution restriction for this one

Description: Drills the array of tiles in the mine.

**Impulse: None as it is only activated by Auto_Mine_Layers**

```BURyaWxsAAAAAAAAAAAFAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQEBWRyaWxsDmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BApkcmlsbGFycmF5Dmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BApkcmlsbGFycmF5DmFyaXRobWV0aWMuaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BApkcmlsbGFycmF5CGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAAPZ2VuZXJpYy5leGVjdXRlDnRlcm5hcnkuc3RyaW5nDmNvbXBhcmlzb24uaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQEBWRyaWxsCGNvbnN0YW50BAE8CGNvbnN0YW50Ag8AAAAIY29uc3RhbnQEBURyaWxsCGNvbnN0YW50BAAIbWluZS5kaWcOYXJpdGhtZXRpYy5pbnQNbG9jYWwuaW50LmdldAhjb25zdGFudAQFZHJpbGwIY29uc3RhbnQEA21vZAhjb25zdGFudAIEAAAADmFyaXRobWV0aWMuaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQEBWRyaWxsCGNvbnN0YW50BAEvCGNvbnN0YW50AgQAAAAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCBAAAABJ0b3duLndpbmRvdy5pc29wZW4IY29uc3RhbnQEBG1pbmU=```

**Asteroid_Rewards**

Description: Opens each asteroid and claims rewards. 

**Impulse: A. Is also activated by Auto_Mine**

```EEFzdGVyb2lkX3Jld2FyZHMBAAAABWtleS5hAgAAABJ0b3duLndpbmRvdy5pc29wZW4IY29uc3RhbnQEBG1pbmUPY29tcGFyaXNvbi5ib29sDmNvbXBhcmlzb24uaW50DXNjcmVlbi5oZWlnaHQIY29uc3RhbnQEAj09CGNvbnN0YW50AjgEAAAIY29uc3RhbnQEASYOY29tcGFyaXNvbi5pbnQMc2NyZWVuLndpZHRoCGNvbnN0YW50BAI9PQhjb25zdGFudAKABwAACgAAABBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BARzbG90CGNvbnN0YW50AwAAAAAAAAAAEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEAXkIY29uc3RhbnQDAAAAAABwjEAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQFZGVsdGEIY29uc3RhbnQDAAAAAAAASUAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQBeRFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAF5CGNvbnN0YW50BAEtEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEBWRlbHRhDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAD4kUAIY29uc3RhbnQDAAAAAACwjUANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAPiRQBBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAF5DWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAACUlkAIY29uc3RhbnQDAAAAAAAohEAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQEc2xvdBFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BARzbG90CGNvbnN0YW50BAErCGNvbnN0YW50AwAAAAAAAPA/DmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AgQAAAAOY29tcGFyaXNvbi5pbnQDZDJpEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEBHNsb3QIY29uc3RhbnQEATwNbWluZS5jbHVzdGVycw1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAA+JFACGNvbnN0YW50AwAAAAAAsI1A```

**Electricity_Lab**

Description: The part of the script that upgrades the conductors. Turns off at the end of upgrades for one prestige or end early by pressing 9 to activate the off script. 

**Impulse: None Triggered from second script.**

```D2VsZWN0cmljaXR5X2xhYgAAAAACAAAAEnRvd24ud2luZG93Lmlzb3Blbghjb25zdGFudAQKbGFib3JhdG9yeQ9jb21wYXJpc29uLmJvb2wOY29tcGFyaXNvbi5pbnQNc2NyZWVuLmhlaWdodAhjb25zdGFudAQCPT0IY29uc3RhbnQCOAQAAAhjb25zdGFudAQBJg5jb21wYXJpc29uLmludAxzY3JlZW4ud2lkdGgIY29uc3RhbnQEAj09CGNvbnN0YW50AoAHAAANAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQECmVsZWN0cm9kZXMIY29uc3RhbnQCBQAAAA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAmIhACGNvbnN0YW50AwAAAAAACIhADWxvY2FsLmludC5zZXQIY29uc3RhbnQECmVsZWN0cm9kZXMOYXJpdGhtZXRpYy5pbnQNbG9jYWwuaW50LmdldAhjb25zdGFudAQKZWxlY3Ryb2Rlcwhjb25zdGFudAQBKwhjb25zdGFudAIBAAAADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AgIAAAAOY29tcGFyaXNvbi5pbnQNbG9jYWwuaW50LmdldAhjb25zdGFudAQKZWxlY3Ryb2Rlcwhjb25zdGFudAQBPAhjb25zdGFudAIUAAAAEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEAXkIY29uc3RhbnQDAAAAAAAYikAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQCeTIIY29uc3RhbnQDAAAAAAAAAAANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAEiCQBBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAF5DWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAACYiEAIY29uc3RhbnQDAAAAAABohUAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQBeRFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAF5CGNvbnN0YW50BAEtCGNvbnN0YW50AwAAAAAAACRADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AgcAAAARY29tcGFyaXNvbi5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQBeQhjb25zdGFudAQBPghjb25zdGFudAMAAAAAANiDQBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAJ5MhFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAJ5Mghjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAADwPxBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAF5CGNvbnN0YW50AwAAAAAAGIpADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AgcAAAARY29tcGFyaXNvbi5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQCeTIIY29uc3RhbnQEATwIY29uc3RhbnQDAAAAAAAAGEA=```

**Electricity_Lab2**

Description: Only works with completely new lab (I might fix this later) as it will select the 2nd set and go from there skipping the first set if they are already purchased. Buys every conductor and upgrades them by calling on the other script. Turns off at the end of upgrades for one prestige or end early by pressing 9 to activate the off script. 

**Impulse: E**

```EGVsZWN0cmljaXR5X2xhYjIBAAAABWtleS5lAgAAABJ0b3duLndpbmRvdy5pc29wZW4IY29uc3RhbnQECmxhYm9yYXRvcnkPY29tcGFyaXNvbi5ib29sDmNvbXBhcmlzb24uaW50DXNjcmVlbi5oZWlnaHQIY29uc3RhbnQEAj09CGNvbnN0YW50AjgEAAAIY29uc3RhbnQEASYOY29tcGFyaXNvbi5pbnQMc2NyZWVuLndpZHRoCGNvbnN0YW50BAI9PQhjb25zdGFudAKABwAAEwAAAA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAiIpACGNvbnN0YW50AwAAAAAA+INADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAD4i0AIY29uc3RhbnQDAAAAAADwg0ANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAALCMQAhjb25zdGFudAMAAAAAAPCDQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAII1ACGNvbnN0YW50AwAAAAAA8INADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABAfkAIY29uc3RhbnQDAAAAAADwg0ATZ2VuZXJpYy5leGVjdXRlc3luYwhjb25zdGFudAQPZWxlY3RyaWNpdHlfbGFiDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABojEAIY29uc3RhbnQDAAAAAADIikANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAANCCQAhjb25zdGFudAMAAAAAABiEQBNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BA9lbGVjdHJpY2l0eV9sYWINZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAFCMQAhjb25zdGFudAMAAAAAAOCKQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAASIZACGNvbnN0YW50AwAAAAAA+INAE2dlbmVyaWMuZXhlY3V0ZXN5bmMIY29uc3RhbnQED2VsZWN0cmljaXR5X2xhYg1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAUIxACGNvbnN0YW50AwAAAAAA6IpADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAACwiUAIY29uc3RhbnQDAAAAAAAYhEATZ2VuZXJpYy5leGVjdXRlc3luYwhjb25zdGFudAQPZWxlY3RyaWNpdHlfbGFiDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAABgjEAIY29uc3RhbnQDAAAAAADYikANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAGCNQAhjb25zdGFudAMAAAAAADCEQBNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BA9lbGVjdHJpY2l0eV9sYWINZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAICMQAhjb25zdGFudAMAAAAAAMiKQA==```

**Stones**

Description: Clicks on the position of the 400h skip when infinity perk window is open. Creates 50 scripts to click very fast for fast recharging stones. Turn off by pressing 9 to activate the off script. 

**Impulse: 8**

```BnN0b25lcwEAAAAFa2V5LjgCAAAADmNvbXBhcmlzb24uaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAZzdG9uZXMIY29uc3RhbnQEATwIY29uc3RhbnQCMgAAAA9jb21wYXJpc29uLmJvb2wOY29tcGFyaXNvbi5pbnQNc2NyZWVuLmhlaWdodAhjb25zdGFudAQCPT0IY29uc3RhbnQCOAQAAAhjb25zdGFudAQBJg5jb21wYXJpc29uLmludAxzY3JlZW4ud2lkdGgIY29uc3RhbnQEAj09CGNvbnN0YW50AoAHAAAEAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BAZzdG9uZXMOYXJpdGhtZXRpYy5pbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBnN0b25lcwhjb25zdGFudAQBKwhjb25zdGFudAIBAAAAD2dlbmVyaWMuZXhlY3V0ZQhjb25zdGFudAQGc3RvbmVzDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAgnEAIY29uc3RhbnQDAAAAAAAwdkAMZ2VuZXJpYy5nb3RvCGNvbnN0YW50AgMAAAA=```

**Stone_3**

Description: Clicks water stone repeatedly. Turn off by pressing 9 to activate the off script. 

**Impulse: 7**

```B3N0b25lXzMBAAAABWtleS43AQAAAA9jb21wYXJpc29uLmJvb2wOY29tcGFyaXNvbi5pbnQNc2NyZWVuLmhlaWdodAhjb25zdGFudAQCPT0IY29uc3RhbnQCOAQAAAhjb25zdGFudAQBJg5jb21wYXJpc29uLmludAxzY3JlZW4ud2lkdGgIY29uc3RhbnQEAj09CGNvbnN0YW50AoAHAAACAAAADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAgnEAIY29uc3RhbnQDAAAAAAC4ikAPZ2VuZXJpYy5leGVjdXRlCGNvbnN0YW50BAdzdG9uZV8z```

**Off**

Description: Turns off all of my repeating scripts above and unsets the Global variables for them.

**Impulse: 9**

```A29mZgEAAAAFa2V5LjkAAAAABwAAAAxnZW5lcmljLnN0b3AIY29uc3RhbnQEBnN0b25lcwxnZW5lcmljLnN0b3AIY29uc3RhbnQEB3N0b25lXzMMZ2VuZXJpYy5zdG9wCGNvbnN0YW50BBF3b3Jrc2hvcF9lbGVtZW50cwxnZW5lcmljLnN0b3AIY29uc3RhbnQECUF1dG9fbWluZQxnZW5lcmljLnN0b3AIY29uc3RhbnQED2VsZWN0cmljaXR5X2xhYgxnZW5lcmljLnN0b3AIY29uc3RhbnQEEGVsZWN0cmljaXR5X2xhYjIMZ2xvYmFsLnVuc2V0CGNvbnN0YW50BAZzdG9uZXM=```

**workshop_elements**

Description: Clicks between essence purchase button and enemies destroyed botton repeatedly for selected element only (can change elements while running).

**Impulse: 6**

```EXdvcmtzaG9wX2VsZW1lbnRzAQAAAAVrZXkuNgIAAAASdG93bi53aW5kb3cuaXNvcGVuCGNvbnN0YW50BAh3b3Jrc2hvcA9jb21wYXJpc29uLmJvb2wOY29tcGFyaXNvbi5pbnQNc2NyZWVuLmhlaWdodAhjb25zdGFudAQCPT0IY29uc3RhbnQCOAQAAAhjb25zdGFudAQBJg5jb21wYXJpc29uLmludAxzY3JlZW4ud2lkdGgIY29uc3RhbnQEAj09CGNvbnN0YW50AoAHAAADAAAADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAwgUAIY29uc3RhbnQDAAAAAACAQUANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAADCBQAhjb25zdGFudAMAAAAAAEBfQA9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEEXdvcmtzaG9wX2VsZW1lbnRz```

**tower upgrades**

Description: Clicks all disables aside from electric from bottom to top, and upgrades damage and health shields 13 times at 25x each. 

Requires: 1920x1080 and 0xp disable costs

**Impulse: New  Round**

```DnRvd2VyIHVwZ3JhZGVzAQAAAA1nYW1lLm5ld3JvdW5kAQAAAA9jb21wYXJpc29uLmJvb2wOY29tcGFyaXNvbi5pbnQNc2NyZWVuLmhlaWdodAhjb25zdGFudAQCPT0IY29uc3RhbnQCOAQAAAhjb25zdGFudAQBJg5jb21wYXJpc29uLmludAxzY3JlZW4ud2lkdGgIY29uc3RhbnQEAj09CGNvbnN0YW50AoAHAAAQAAAADGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAADwPw1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAA0HNACGNvbnN0YW50AwAAAAAAsHhADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAADgb0AIY29uc3RhbnQDAAAAAAAAQ0ANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAIBaQAhjb25zdGFudAMAAAAAAOB3QA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAwGdACGNvbnN0YW50AwAAAAAA4HhADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAACAX0AIY29uc3RhbnQDAAAAAACgfUANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAGBnQAhjb25zdGFudAMAAAAAABB/QA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAwGdACGNvbnN0YW50AwAAAAAAWINADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAADAVEAIY29uc3RhbnQDAAAAAADwhkANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAIBkQAhjb25zdGFudAMAAAAAACCHQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAQFRACGNvbnN0YW50AwAAAAAA8IlADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAADgZkAIY29uc3RhbnQDAAAAAABwikANbG9jYWwuaW50LnNldAhjb25zdGFudAQFY291bnQOYXJpdGhtZXRpYy5pbnQNbG9jYWwuaW50LmdldAhjb25zdGFudAQFY291bnQIY29uc3RhbnQEASsIY29uc3RhbnQCAQAAAA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAwGtACGNvbnN0YW50AwAAAAAAyI1ADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAACgbEAIY29uc3RhbnQDAAAAAABQj0AOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCDQAAAA5jb21wYXJpc29uLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAVjb3VudAhjb25zdGFudAQBPAhjb25zdGFudAINAAAA```

**ABANDONED/OBSOLETE SCRIPTS**

<del>Auto_Asteroid_Farming

<del>Description: Farms asteroids with a simple timer to change timing change variable Delete_Cycle_Timer (default 60 here) to disired time between deleting an asteroid and scaning a new one. 

<del>Impulse: M

<del>```FUF1dG9fQXN0ZXJvaWRfRmFybWluZwEAAAAFa2V5Lm0AAAAACgAAABBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BBJkZWxldGVfY3ljbGVfdGltZXIIY29uc3RhbnQDAAAAAAAATkAQdG93bi53aW5kb3cuc2hvdwhjb25zdGFudAQEbWluZQhjb25zdGFudAEBDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAD4kUAIY29uc3RhbnQDAAAAAACwjUANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAPiRQAhjb25zdGFudAMAAAAAAOCKQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAlJZACGNvbnN0YW50AwAAAAAAKIRADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAD4kUAIY29uc3RhbnQDAAAAAACwjUATbWluZS5jbHVzdGVyLnJlbW92ZQhjb25zdGFudAIBAAAADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAIgUAIY29uc3RhbnQDAAAAAACAQUAMZ2VuZXJpYy53YWl0EGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEEmRlbGV0ZV9jeWNsZV90aW1lcgxnZW5lcmljLmdvdG8IY29uc3RhbnQCAwAAAA==```

<del>Auto_Asteroid_Farming

<del>Description: This version toggles on and off with the same impulse but I haven't tested it yet so I am leaving the version above until I know it works. Farms asteroids with a simple timer to change timing change variable Delete_Cycle_Timer (default 60 here) to disired time between deleting an asteroid and scaning a new one. 

<del>Impulse: M

<del>```FUF1dG9fQXN0ZXJvaWRfRmFybWluZwEAAAAFa2V5Lm0AAAAADQAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQedHVybl9vZmZfYXV0b19hc3Rlcm9pZF9mYXJtaW5nDmFyaXRobWV0aWMuaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BB50dXJuX29mZl9hdXRvX2FzdGVyb2lkX2Zhcm1pbmcIY29uc3RhbnQEASsIY29uc3RhbnQCAQAAABBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BBJkZWxldGVfY3ljbGVfdGltZXIIY29uc3RhbnQDAAAAAAAATkAQdG93bi53aW5kb3cuc2hvdwhjb25zdGFudAQEbWluZQhjb25zdGFudAEBDWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAD4kUAIY29uc3RhbnQDAAAAAACwjUANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAPiRQAhjb25zdGFudAMAAAAAAOCKQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAlJZACGNvbnN0YW50AwAAAAAAKIRADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAD4kUAIY29uc3RhbnQDAAAAAACwjUATbWluZS5jbHVzdGVyLnJlbW92ZQhjb25zdGFudAIBAAAADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAIgUAIY29uc3RhbnQDAAAAAACAQUAMZ2VuZXJpYy53YWl0EGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEEmRlbGV0ZV9jeWNsZV90aW1lcg5nZW5lcmljLmdvdG9pZghjb25zdGFudAIEAAAADmNvbXBhcmlzb24uaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BB50dXJuX29mZl9hdXRvX2FzdGVyb2lkX2Zhcm1pbmcIY29uc3RhbnQEAj09CGNvbnN0YW50AgEAAAAOZ2xvYmFsLmludC5zZXQIY29uc3RhbnQEHnR1cm5fb2ZmX2F1dG9fYXN0ZXJvaWRfZmFybWluZwhjb25zdGFudAIAAAAADGdlbmVyaWMuc3RvcAhjb25zdGFudAQVQXV0b19Bc3Rlcm9pZF9GYXJtaW5n```

<del>Auto_Mine
Set up required: Allocate perks for mining. Have a worker on each asteroid slot. Go to second floor of mine(you don't have to stay there just can't leave on lower floor), Have 14 asteroids, have infinity stone perk window open within the stone page. Change variable: Delete_Cycle_Count to desired number of cycles through the script between deleting the first asteroid(default is 3) faster pp boost will warrent lowering it while slower scan speed or pp boost will make you want to raise it. Check quick scan. 

<del>Description: Opens up the mine page which activates Auto_Mine_Layers and Drill scripts, activates Asteroid_Rewards, deletes first asteroid slot (if number of cycles before deletion have passed), starts scanning new asteriod (if number of cycles before deletion have passed), waits for drill to finish then leaves the mine to go to the infinity stone page where it activates the earth stone and then it repeats. Turn off by pressing 9 to activate the off script. 

<del>Impulse: M

<del>```CUF1dG9fbWluZQEAAAAFa2V5Lm0AAAAAEAAAAA1sb2NhbC5pbnQuc2V0CGNvbnN0YW50BAhhc3Rlcm9pZAhjb25zdGFudAIBAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQEEmRlbGV0ZV9jeWNsZV9jb3VudAhjb25zdGFudAIDAAAAEHRvd24ud2luZG93LnNob3cIY29uc3RhbnQEBG1pbmUIY29uc3RhbnQBAQ9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEEEFzdGVyb2lkX3Jld2FyZHMRZ2VuZXJpYy53YWl0dW50aWwOY29tcGFyaXNvbi5pbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyCGNvbnN0YW50BAI9PQhjb25zdGFudAINAAAADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AgoAAAAPY29tcGFyaXNvbi5ib29sDmNvbXBhcmlzb24uaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQECGFzdGVyb2lkCGNvbnN0YW50BAE8DWxvY2FsLmludC5nZXQIY29uc3RhbnQEEmRlbGV0ZV9jeWNsZV9jb3VudAhjb25zdGFudAQCPT0IY29uc3RhbnQBARNtaW5lLmNsdXN0ZXIucmVtb3ZlCGNvbnN0YW50AgEAAAANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAAiBQAhjb25zdGFudAMAAAAAAIBBQA1sb2NhbC5pbnQuc2V0CGNvbnN0YW50BAhhc3Rlcm9pZAhjb25zdGFudAIAAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQECGFzdGVyb2lkDmFyaXRobWV0aWMuaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQECGFzdGVyb2lkCGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAAQdG93bi53aW5kb3cuc2hvdwhjb25zdGFudAQEbWluZQhjb25zdGFudAEADGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAADgPw1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAiJ1ACGNvbnN0YW50AwAAAAAAOINADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAAgnEAIY29uc3RhbnQDAAAAAACoi0ANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAJydQAhjb25zdGFudAMAAAAAAHyQQAxnZW5lcmljLmdvdG8IY29uc3RhbnQCAwAAAA==```

<del>Auto_Mine with faster options

<del>Description: Same as above but with the option to change Delete_Cycle_Count (default 0 here) to less than 1 and delete/ scan two asteroids per cycle. Needs to have max upgrades with high pp boost to work though.

<del>Impulse: M

<del>```CUF1dG9fbWluZQEAAAAFa2V5Lm0AAAAAGAAAAA1sb2NhbC5pbnQuc2V0CGNvbnN0YW50BAhhc3Rlcm9pZAhjb25zdGFudAIBAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQEEmRlbGV0ZV9jeWNsZV9jb3VudAhjb25zdGFudAIAAAAAEHRvd24ud2luZG93LnNob3cIY29uc3RhbnQEBG1pbmUIY29uc3RhbnQBARNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BBBBc3Rlcm9pZF9yZXdhcmRzDmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AggAAAAPY29tcGFyaXNvbi5ib29sDmNvbXBhcmlzb24uaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQEEmRlbGV0ZV9jeWNsZV9jb3VudAhjb25zdGFudAQCPj0IY29uc3RhbnQCAQAAAAhjb25zdGFudAQCPT0IY29uc3RhbnQBARNtaW5lLmNsdXN0ZXIucmVtb3ZlCGNvbnN0YW50AgEAAAANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAAiBQAhjb25zdGFudAMAAAAAAIBBQA5nZW5lcmljLmdvdG9pZghjb25zdGFudAIPAAAAD2NvbXBhcmlzb24uYm9vbA5jb21wYXJpc29uLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAhhc3Rlcm9pZAhjb25zdGFudAQBPA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BBJkZWxldGVfY3ljbGVfY291bnQIY29uc3RhbnQEAj09CGNvbnN0YW50AQEMZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAAABADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAAD4kUAIY29uc3RhbnQDAAAAAADgikANZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAJSWQAhjb25zdGFudAMAAAAAACiEQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAA+JFACGNvbnN0YW50AwAAAAAAsI1AE21pbmUuY2x1c3Rlci5yZW1vdmUIY29uc3RhbnQCAQAAAA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAACIFACGNvbnN0YW50AwAAAAAAgEFAEWdlbmVyaWMud2FpdHVudGlsDmNvbXBhcmlzb24uaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAVsYXllcghjb25zdGFudAQCPT0IY29uc3RhbnQCDQAAAA5nZW5lcmljLmdvdG9pZghjb25zdGFudAISAAAAD2NvbXBhcmlzb24uYm9vbA5jb21wYXJpc29uLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAhhc3Rlcm9pZAhjb25zdGFudAQBPA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BBJkZWxldGVfY3ljbGVfY291bnQIY29uc3RhbnQEAj09CGNvbnN0YW50AQENbG9jYWwuaW50LnNldAhjb25zdGFudAQIYXN0ZXJvaWQIY29uc3RhbnQCAAAAAA1sb2NhbC5pbnQuc2V0CGNvbnN0YW50BAhhc3Rlcm9pZA5hcml0aG1ldGljLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAhhc3Rlcm9pZAhjb25zdGFudAQBKwhjb25zdGFudAIBAAAAEHRvd24ud2luZG93LnNob3cIY29uc3RhbnQEBG1pbmUIY29uc3RhbnQBAAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAA4D8NZ2VuZXJpYy5jbGljaw52ZWMuZnJvbUNvb3Jkcwhjb25zdGFudAMAAAAAAIidQAhjb25zdGFudAMAAAAAADiDQA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAAIJxACGNvbnN0YW50AwAAAAAAqItADWdlbmVyaWMuY2xpY2sOdmVjLmZyb21Db29yZHMIY29uc3RhbnQDAAAAAACcnUAIY29uc3RhbnQDAAAAAAB8kEAMZ2VuZXJpYy5nb3RvCGNvbnN0YW50AgMAAAA=```
