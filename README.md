# TPT2-Scripts
Scripts for The Perfect Tower 2

Almost all of these scripts require 1920 x 1080 resolution with Dynamic UI Scaling turned on.

Auto_Mine
Set up required: Go to second floor of mine(you don't have to stay there just can't leave on lower floor), Have 10 asteroids, have infinity stone perk window open within the stone page. Change variable: Delete_Cycle_Count to desired number of cycles through the script between deleting the first asteroid(default is 3) faster pp boost will warrent lowering it while slower scan speed or pp boost will make you want to raise it. Check quick scan.

Description: Opens up the mine page which activates Auto_Mine_Layers and Drill scripts, activates Asteroid_Rewards, deletes first asteroid slot (if number of cycles before deltion have passed), starts scanning new asteriod (if number of cycles before deltion have passed), waits for drill to finish then leaves the mine to go to the infinity stone page where it activates the earth stone and then it repeats. Turn off by pressing 9 to activate the off script. 

Impulse: M

CUF1dG9fbWluZQEAAAAFa2V5Lm0AAAAAEAAAAA1sb2NhbC5pbnQuc2V0CGNvbnN0YW50BAhBc3Rlcm9pZAhjb25zdGFudAIBAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQEEkRlbGV0ZV9DeWNsZV9Db3VudAhjb25zdGFudAIDAAAAEHRvd24ud2luZG93LnNob3cIY29uc3RhbnQEBG1pbmUIY29uc3RhbnQBAQ9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEEEFzdGVyb2lkX3Jld2FyZHMRZ2VuZXJpYy53YWl0dW50aWwOY29tcGFyaXNvbi5pbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyCGNvbnN0YW50BAI9PQhjb25zdGFudAINAAAADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AgoAAAAPY29tcGFyaXNvbi5ib29sDmNvbXBhcmlzb24uaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQECEFzdGVyb2lkCGNvbnN0YW50BAE8DWxvY2FsLmludC5nZXQIY29uc3RhbnQEEkRlbGV0ZV9DeWNsZV9Db3VudAhjb25zdGFudAQCPT0IY29uc3RhbnQBARNtaW5lLmNsdXN0ZXIucmVtb3ZlCGNvbnN0YW50AgEAAAANZ2VuZXJpYy5jbGljawhjb25zdGFudAUAQAhEAAAMQg1sb2NhbC5pbnQuc2V0CGNvbnN0YW50BAhBc3Rlcm9pZAhjb25zdGFudAIAAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQECEFzdGVyb2lkDmFyaXRobWV0aWMuaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQECEFzdGVyb2lkCGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAANZ2VuZXJpYy5jbGljawhjb25zdGFudAUA4OxEAOCDRAxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAA4D8NZ2VuZXJpYy5jbGljawhjb25zdGFudAUAQOxEAMAZRA1nZW5lcmljLmNsaWNrCGNvbnN0YW50BQAA4UQAQF1EDWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAODsRADgg0QMZ2VuZXJpYy5nb3RvCGNvbnN0YW50AgMAAAA=

Auto_Mine_Layers
Description: Activates when the Mine is opened starts Drill script for each mine array position then opens new layer on each tab until they are all clear. Cleaning turns itself off when you leave the mine as well as unsets the glabal variable for the Drill script.

Impulse: Open Mine

EEF1dG9fTWluZV9sYXllcnMBAAAACW9wZW4ubWluZQAAAAALAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BAVsYXllcghjb25zdGFudAIAAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BApkcmlsbGFycmF5CGNvbnN0YW50AgAAAAAPZ2VuZXJpYy5leGVjdXRlCGNvbnN0YW50BAVEcmlsbBFnZW5lcmljLndhaXR1bnRpbA5jb21wYXJpc29uLmludA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQKZHJpbGxhcnJheQhjb25zdGFudAQCPT0IY29uc3RhbnQCEAAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQFbGF5ZXIOYXJpdGhtZXRpYy5pbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyCGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAAIbWluZS50YWIOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyDW1pbmUubmV3bGF5ZXIMZ2VuZXJpYy5nb3RvC3Rlcm5hcnkuaW50Dm1pbmUuaGFzTGF5ZXJzCGNvbnN0YW50AgcAAAALdGVybmFyeS5pbnQOY29tcGFyaXNvbi5pbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBWxheWVyCGNvbnN0YW50BAE8CGNvbnN0YW50Ag0AAAAIY29uc3RhbnQCBQAAAAhjb25zdGFudAIJAAAADGdlbmVyaWMuc3RvcAhjb25zdGFudAQFRHJpbGwMZ2xvYmFsLnVuc2V0CGNvbnN0YW50BAVMYXllcgxnbG9iYWwudW5zZXQIY29uc3RhbnQECkRyaWxsYXJyYXk=

Drill

Description: Drills the array of tiles in the mine.

Impulse: None as it is only activated by Auto_Mine_Layers

BURyaWxsAAAAAAAAAAAFAAAADWxvY2FsLmludC5zZXQIY29uc3RhbnQEBWRyaWxsDmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BApkcmlsbGFycmF5Dmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BApkcmlsbGFycmF5DmFyaXRobWV0aWMuaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BApkcmlsbGFycmF5CGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAAPZ2VuZXJpYy5leGVjdXRlDnRlcm5hcnkuc3RyaW5nDmNvbXBhcmlzb24uaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQEBWRyaWxsCGNvbnN0YW50BAE8CGNvbnN0YW50Ag8AAAAIY29uc3RhbnQEBURyaWxsCGNvbnN0YW50BAAIbWluZS5kaWcOYXJpdGhtZXRpYy5pbnQNbG9jYWwuaW50LmdldAhjb25zdGFudAQFZHJpbGwIY29uc3RhbnQEA21vZAhjb25zdGFudAIEAAAADmFyaXRobWV0aWMuaW50DWxvY2FsLmludC5nZXQIY29uc3RhbnQEBWRyaWxsCGNvbnN0YW50BAEvCGNvbnN0YW50AgQAAAAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCBAAAABJ0b3duLndpbmRvdy5pc29wZW4IY29uc3RhbnQEBG1pbmU=

Asteroid_Rewards

Description: Opens each asteroid and claims rewards. 

Impulse: A. Is also activated by Auto_Mine

EEFzdGVyb2lkX3Jld2FyZHMBAAAABWtleS5hAQAAABJ0b3duLndpbmRvdy5pc29wZW4IY29uc3RhbnQEBG1pbmUKAAAAEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEBHNsb3QIY29uc3RhbnQDAAAAAAAAAAAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQBeQhjb25zdGFudAMAAAAAAHCMQBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAVkZWx0YQhjb25zdGFudAMAAAAAAABJQBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAF5EWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEAXkIY29uc3RhbnQEAS0QbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQFZGVsdGENZ2VuZXJpYy5jbGljawhjb25zdGFudAUAwI9EAIBtRA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAA+JFAEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEAXkNZ2VuZXJpYy5jbGljawhjb25zdGFudAUAoLREAEAhRBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BARzbG90EWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEBHNsb3QIY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAAAA8D8OZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCBAAAAA5jb21wYXJpc29uLmludANkMmkQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQEc2xvdAhjb25zdGFudAQBPA1taW5lLmNsdXN0ZXJzDWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAMCPRACAbUQ=

Electricity_Lab

Description: The part of the script that upgrades the conductors. Turns off at the end of upgrades for one prestige or end early by pressing 9 to activate the off script. 

Impulse: None only activated from 2nd script

D2VsZWN0cmljaXR5X2xhYgAAAAABAAAAEnRvd24ud2luZG93Lmlzb3Blbghjb25zdGFudAQKbGFib3JhdG9yeQ0AAAANbG9jYWwuaW50LnNldAhjb25zdGFudAQKZWxlY3Ryb2Rlcwhjb25zdGFudAIFAAAADWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAMBERABAQEQNbG9jYWwuaW50LnNldAhjb25zdGFudAQKZWxlY3Ryb2Rlcw5hcml0aG1ldGljLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAplbGVjdHJvZGVzCGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCAgAAAA5jb21wYXJpc29uLmludA1sb2NhbC5pbnQuZ2V0CGNvbnN0YW50BAplbGVjdHJvZGVzCGNvbnN0YW50BAE8CGNvbnN0YW50AhQAAAAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQBeQhjb25zdGFudAMAAAAAABiKQBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAJ5Mghjb25zdGFudAMAAAAAAAAAAA1nZW5lcmljLmNsaWNrDnZlYy5mcm9tQ29vcmRzCGNvbnN0YW50AwAAAAAASIJAEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEAXkNZ2VuZXJpYy5jbGljawhjb25zdGFudAUAwEREAEArRBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAF5EWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEAXkIY29uc3RhbnQEAS0IY29uc3RhbnQDAAAAAAAAJEAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCBwAAABFjb21wYXJpc29uLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAF5CGNvbnN0YW50BAE+CGNvbnN0YW50AwAAAAAA2INAEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEAnkyEWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEAnkyCGNvbnN0YW50BAErCGNvbnN0YW50AwAAAAAAAPA/EGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEAXkIY29uc3RhbnQDAAAAAAAYikAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCBwAAABFjb21wYXJpc29uLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAJ5Mghjb25zdGFudAQBPAhjb25zdGFudAMAAAAAAAAYQA==

Electricity_Lab2

Description: Only works with completely new lab (I might fix this later) as it will select the 2nd set and go from there skipping the first set if they are already purchased. Buys every conductor and upgrades them by calling on the other script. Turns off at the end of upgrades for one prestige or end early by pressing 9 to activate the off script. 

Impulse: E

EGVsZWN0cmljaXR5X2xhYjIBAAAABWtleS5lAAAAABMAAAANZ2VuZXJpYy5jbGljawhjb25zdGFudAUAQFREAMAfRA1nZW5lcmljLmNsaWNrCGNvbnN0YW50BQDAX0QAgB9EDWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAIBlRACAH0QNZ2VuZXJpYy5jbGljawhjb25zdGFudAUAAGlEAIAfRA1nZW5lcmljLmNsaWNrCGNvbnN0YW50BQAA8kMAgB9EE2dlbmVyaWMuZXhlY3V0ZXN5bmMIY29uc3RhbnQED2VsZWN0cmljaXR5X2xhYg1nZW5lcmljLmNsaWNrCGNvbnN0YW50BQBAY0QAQFZEDWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAIAWRADAIEQTZ2VuZXJpYy5leGVjdXRlc3luYwhjb25zdGFudAQPZWxlY3RyaWNpdHlfbGFiDWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAIBiRAAAV0QNZ2VuZXJpYy5jbGljawhjb25zdGFudAUAQDJEAMAfRBNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BA9lbGVjdHJpY2l0eV9sYWINZ2VuZXJpYy5jbGljawhjb25zdGFudAUAgGJEAEBXRA1nZW5lcmljLmNsaWNrCGNvbnN0YW50BQCATUQAwCBEE2dlbmVyaWMuZXhlY3V0ZXN5bmMIY29uc3RhbnQED2VsZWN0cmljaXR5X2xhYg1nZW5lcmljLmNsaWNrCGNvbnN0YW50BQAAY0QAwFZEDWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAABrRACAIUQTZ2VuZXJpYy5leGVjdXRlc3luYwhjb25zdGFudAQPZWxlY3RyaWNpdHlfbGFiDWdlbmVyaWMuY2xpY2sIY29uc3RhbnQFAABkRABAVkQ=

Stones

Description: Clicks on the position of the 400h skip when infinity perk window is open. Creates 50 scripts to click very fast for fast recharging stones. Turn off by pressing 9 to activate the off script. 

Impulse: 8

BnN0b25lcwEAAAAFa2V5LjgBAAAADmNvbXBhcmlzb24uaW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAZzdG9uZXMIY29uc3RhbnQEATwIY29uc3RhbnQCMgAAAAQAAAAOZ2xvYmFsLmludC5zZXQIY29uc3RhbnQEBnN0b25lcw5hcml0aG1ldGljLmludA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQGc3RvbmVzCGNvbnN0YW50BAErCGNvbnN0YW50AgEAAAAPZ2VuZXJpYy5leGVjdXRlCGNvbnN0YW50BAZzdG9uZXMNZ2VuZXJpYy5jbGljawhjb25zdGFudAUAAOFEAICxQwxnZW5lcmljLmdvdG8IY29uc3RhbnQCAwAAAA==

Stone_3

Description: Clicks water stone repeatedly. Turn off by pressing 9 to activate the off script. 

Impulse: 7

B3N0b25lXzMBAAAABWtleS43AAAAAAIAAAANZ2VuZXJpYy5jbGljawhjb25zdGFudAUAAOFEAMBVRA9nZW5lcmljLmV4ZWN1dGUIY29uc3RhbnQEB3N0b25lXzM=

Off

Description: Turns off all of my repeating scripts above and unsets the Global variables for them.

Impulse: 9

A29mZgEAAAAFa2V5LjkAAAAABwAAAAxnZW5lcmljLnN0b3AIY29uc3RhbnQEBnN0b25lcwxnZW5lcmljLnN0b3AIY29uc3RhbnQEB3N0b25lXzMMZ2VuZXJpYy5zdG9wCGNvbnN0YW50BBF3b3Jrc2hvcF9lbGVtZW50cwxnZW5lcmljLnN0b3AIY29uc3RhbnQECUF1dG9fbWluZQxnZW5lcmljLnN0b3AIY29uc3RhbnQED2VsZWN0cmljaXR5X2xhYgxnZW5lcmljLnN0b3AIY29uc3RhbnQEEGVsZWN0cmljaXR5X2xhYjIMZ2xvYmFsLnVuc2V0CGNvbnN0YW50BAZzdG9uZXM=
