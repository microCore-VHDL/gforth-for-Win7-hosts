# gforth for Win7
The uForth cross-compiler and the uCore debugger run on a host computer, 
eventually transferring object code to the target system via an RS232 umbilical for execution.<BR><BR>
The host software runs on top of gforth-0.6.2.<BR>
Unfortunately, Microsoft's docker does not support serial links and 
therefore, you need to install gforth on Windows from this respository's gforth.exe installation file 
following the instructions in howto-install.txt. 
Also, this version of gforth does no longer run on Win10!<BR><BR>
For Linux or MacOS hosts you should pull the docker file microcore/gforth_062.<BR> 
On Linux you can start the software using the gforth062.sh script. 
It defines the location of the RS232 interface.<BR> 
Depending on your OS and port, you may have to modify umbilical.fs accordingly.
