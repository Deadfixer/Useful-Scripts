Useful Scripts
============

<u>Linux, Bash:</u>

* <b>vsftpd.sh</b> -- fast vsftpd config for Debian server with /var/ftp directory, ftpuser group
* <b>deb-kern-up.sh</b> -- Debian distro kernel update script, don't forget to change version to keep it up to date
* <b>simple_apache_firewall.sh</b> -- Simple firewall script for apache to block IPs with lots requests from log
<hr />

<u>Windows, PowerShell:</u>

* <b>Windows Logs Extracting</b> -- PowerShell script to easily extract required logs preformated for quick parsing into text file.
Usage:
<pre>./winlogs.ps1 list  #will show all available logs
     ./winlogs.ps1 "Security" 25  #will store 25 security log events into file with mask "date_logtype.txt" i.e: 20160303_security.txt</pre>