This is a .bat file for constant run that loops the running of the server. Or in other words restarts the server when it stops.


[code]color 0E
title STARTING NUKKIT
@echo off
:start
java -Xmx1024M -jar nukkit.jar -o true
title RESTARTING NUKKIT
goto start[/code]

​
How to use:
Copy the code above and put it in to a .bat file called run.
​
Note: The nukkit jar file must be called nukkit.jar or this will not run.
