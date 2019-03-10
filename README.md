# keepass-exfiltrate
A patch to backdoor keepass 2.x that writes to file the keyfile location and password for a database on disk or remote share. This tool was usefull during an engagement where the auditor had full access only to the Keepass.exe file. 

# Patching

* Clone the Keepass2.x repo (non official https://github.com/dlech/KeePass2.x)
* Edit line number 17 in case you wish to write the key file on a network share
* Apply the patch
* Compile via Visual Studio
* Deploy!
