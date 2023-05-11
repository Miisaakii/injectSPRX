
![alt text](https://i.imgur.com/iveDD5q.png)

A simple tool that can inject any SPRX to your PS3 after have build it on visual studio.
<br><br>
How to use it ?
<br>
In the source of your SPRX go in settings and then go in "Build Events" -> Post-Build Event
In "Command Line" add this: IF EXIST "$(TargetDir)run.exe"  "$(TargetDir)run.exe"
<br>
<br>
![alt text](https://i.imgur.com/ofLzp6c.png)
<br>
<br>
save it then go into the output of your source
add the file (inject.exe, run.exe settings.txt) and edit the file (settings.txt) for your SPRX
<br>
<br>
useLoader=true <- don't touch
<br>
192.168.1.17 <- your console IP
<br>
OasisSPRX.sprx <- Name of SPRX you build
<br>
OasisSPRX.sprx <- Name of SPRX you want to add in tmp
<br>
/dev_hdd0/tmp/ <- Path where the sprx go in your console
<br>

save the file and then enjoy !

/!\ if you have any error, try to install webMAN 1.47.37 MOD in FULL mode /!\
