# Netcat_Backdoor

Have the ncat.exe file on both the host machine and slave machine.

Edit the ncat_frontdoor.bat file
Replace 'ip_of_slave' with the local network ip address of the slave machine which will be running ncat_backdoor.

Save as all files with the .bat extension.

Make sure ncat.exe is in the same location as both batch files.

Run ncat_backdoor on slave machine.
Run ncat_frontdoor on host machine.


To test type some commands on the host machine like 'whoami'
