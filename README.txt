# ESX-HealthCheck
ESX HealthCheck Script is a shell script that collects data about a VMWare ESX 3 or 4 host.

This script has been staged at SourceForge (https://sourceforge.net/projects/esxhealthscript/files/esxhealthscript/)
for over 10 years now.  Originally created by Anders Mikkelsen, I started updating it for my
own environment and sent the updates back to the project.  I'm placing a copy here for my 
own reference.  

This version (49) was the last one released back on 01-08-2010.  I "may" start updating it
"if" I have time.  I've moved away from ESX admin as a primary function so this is not as important
in my work now.

-------------------------------------------------------------

The collection is done by a bunch of ordinary unix-commands and some vmware tools.

By default the HTML output is saved in the local host servers Tomcat web server and 
a link may be added to present a clickable URL.  The report is also optionally emailed
to a preconfigured email acount(s). The email function may be disabled via the 
configuration file.

The script has beet tested on ESX version 3 thru 4 update 1 and the script automatically
detects and formats itself for the version of ESX being used.



