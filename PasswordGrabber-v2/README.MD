PasswordGrabber v2

Source: https://github.com/hak5/bashbunny-payloads/tree/master/payloads/library/credentials/PasswordGrabber

I've modified this payload to disable Windows Defender (only) when the Powershell script will run.
After finishing Windows Defender will be activated again.

Tested on Windows 10 Home v1803 x64

Clear instructions:
For personal reasons I changed the payload location in payload.txt. Scroll down and set payload\\switch1\ . Set this value back to $SWITCH_POSITION if you want.

Download LaZagne_x86.exe and LaZagne_x86.exe (Windows.zip) from this source -> https://github.com/AlessandroZ/LaZagne/releases
NOTE: Disable your AV/Firewall software. Best is to download via FireFox and allow it to download. 
To prefend this file to be deleted, save the file to for example your Download folder, add this folder to the whitelist in your AV/Firewall software. So this folder will not be scanned and delete LaZagne everytime.
Rename Lazagne_x64 or x86 to just LaZagne.exe and put it in /tools.

In /switch1 put payload.txt and payload.ps1.
Have fun!