## 3DS CATIA(r) CAA VB.NET weld designation according Russian Standards.
### This is a small add-on that creates a weld designation in accordance with Russian drafting standards. Tested in V5R15 and V5R19 version.

A small setup guide in Russian in the file "Description_RU.pdf".

![Preview image](https://github.com/Lab-V/CATIA_CAA_GOST_WELD_SYMBOL/blob/main/CAA_VBNET_WELD_SYMBOL.png)

The program was tested in Windows XP Professional SP2.
The system contains:

1. Microsoft .NET Framework 3.5 SP1
 + Hotfix for Microsoft .NET Framework 3.5 SP1 (KB953595)
 + Language pack Microsoft .NET Framework 3.5 - RUS

2. Windows Installer 3.1 (KB893803)


Found some "irreparable virtues":

After turning on Windows from "Hibernation" the application did not see running CATIA
- the message "For the application to work, you must first start CATIA".

Solution: restart the CATIA COM server.
Start / Run - "cmd", then go to the CATIA installation folder (..intel_a \ code \ bin),

execute the command "cnext / unregserver"
execute the command "cnext / regserver"

You can find more examples on the forum:
[plm-forum.ru](http://www.plm-forum.ru/forum/)
