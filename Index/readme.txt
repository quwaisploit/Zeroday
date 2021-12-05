Lab By : Muhammad Quwais Saputra

Use it On? Termux

how to run this Lab?
first in termux.. You need to install PHP using 'apt install php -y'

anyway.. im using PHP 8.0.1

After installing PHP is done.. Now you need to setup the server
and run the Code on Browser (ex: localhost:8080 if you are non rooted)
using this command => php -t Zeroday/Index -S localhost:8080

after you execute the script.. just Open your browser and try to input
the url 'localhost:8080'.. if the page is returned "Hack me if you can :)", this is already Done and time to Hack it! if the page is error..
This means you have a problem when Setting down the running page

================= HACKING TIME =================
download the exploit from My database : https://github.com/quwaisploit/exploitdb/blob/master/2021/CVE2021_0603.py

after that.. save the code script as anything you want.

after that.. run the code using python CVE2021_0603.py.
after that.. youll be seeing the Input Program.. like this:
   input the full name of host

right now.. Just input our lab For testing.. Because we Use The Localhost
To our server right now. Im include The http://localhost:8080 as my target

after responds success (200). Just type "tty".. and now you will be able to
remote execution vulnerability :)


CVE  : 2021-0603
VULN : PHP 8.0.1
