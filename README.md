
2 . Perform Passive Reconnaissance
Collect information about a target domain using online tools.Target: example.com,  Tools Needed: whois, nslookup, DNSDumpster

Visit https://www.nslookup.io/
https://www.whois.com/whois/
https://dnsdumpster.com/

put your target site in search box and search 


3.3. Identify Website Technologies
Find technologies used by a website (CMS, server, frameworks).Target: Any website
Tools Needed: Wappalyzer

Download wappalyzer extension from chrome or edge extension , and click wappalyzer, if you want in terminal use 
whatweb <target site>


4. Perform Directory Enumeration
Find hidden directories and files in a web application.Target: http://testphp.vulnweb.com/
Tools Needed: Dirsearch / Gobuster

gobuster dir -u <targetsite> \
  -w /usr/share/dirbuster/wordlists/directory-list-2.3-medium.txt 

(do in linux)


4. . Brute Force Login Page
Attempt login using username/password wordlists.
Target: http://testphp.vulnweb.com/login.php
Tools Needed: Hydra
hydra -l admin -P /usr/shared/wordlists/rockyou.txt <target site> http-post-form "/login.php:username=^USER^&password=^PASS^:F=Invalid" -t 10 -V

6. Perform SQL Injection Attack
Test login form for SQL Injection and bypass authentication

use payload from this site https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SQL%20Injection
and enter payload in both username and password box and click login

7. Identify Information Disclosure
Check for exposed sensitive files (backup/config files). Target: http://testphp.vulnweb.com/

<targetsite>/robots.txt
<targetsite>/sitemap.xml
in web box 

8. Perform IDOR Testing
Access unauthorized data by modifying parameters (like user ID). Target: Any demo web app
Tools Needed: Browser / Burp Suite
intercept login request through burp and change user id or parameter to admin

Csrf and jwt nerla solren




https://chatgpt.com/share/69ec6035-c6dc-8322-8d1f-9a84e092a1e6
