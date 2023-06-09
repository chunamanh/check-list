# ☄️Web-Pentest-Checklist☄️ 
<br><br>

## Client side 🌕
- XSS
- HTML DOM, Response
- CSRF
- CSP Bypass





## Server side 🌏

- Find server
```
X-Powered-By: PHP
X-AspNet-Version: ASP.Net
x-cache, x-status, hit/miss: web cache
X-Application-Context: spring boot
```
- Website directory scanner

    Ex: [dirsearch](https://github.com/maurosoria/dirsearch), [gobuster](https://github.com/OJ/gobuster)

```
/robots.txt, /.well-known/security.txt, /sitemap.xml...
```
- Bruteforce : Weak password
- Scan port 
    Ex: `nmap`
- cookies : JWT-rs256..
- file bak, backup.zip.bak...
- SQL Injection
- Upload file
```
PHP
.php .php3 .php4 .php5 .php7 .htaccess .pht .phtm .phtml .phar .phps
upload zip file with symlink ln -s ../index.php abc.txt; zip -y abc.zip abc.txt
PHP exif_imagetype only check first bytes (magic bytes)
ASP
.aspx .shtml .stm .config .ashx .asmx .aspq .axd .cshtm .cshtml .rem .soap .vbhtm .vbhtml .asa .asp .cer
```
- XXE
- Applications/Frameworks(misused, CVEs..)
- [Privilege Escalation](https://www.hackingarticles.in/exploiting-wildcard-for-privilege-escalation/)
- Logic bugs


