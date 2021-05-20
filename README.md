# ctf-stuff
## Misc
1) SSTV / Robot36 - https://github.com/victim1307/CTF/blob/main/DCTF2021/extraterrestrial.md (slow scan Television to send monochrome/color images over waves)

## Web
1) Server Side Template Injection (SSTI) - SSTI Injection (https://github.com/xxonorg/dCTF2021_Writeup/blob/main/Injection.md)
2) Nessus - to scan home network
3) theharvester - theharvester -d codingliquids.com -b google
Finds everything about a website on google(and other special sites to manage the website's server that is publicly available on the internet).
4) nmap - nmap -sn LINK/24 (use ip instead of link)
  24-->keep constant 24 bits and change last no
  0-->255 8 bits
  IP 8bits.8bits.8bits.8bits
	xxx.xxx.xxx.yyy keeping x's constant varying y's
  nmap searches active ip addressees before and after you.
  Port scanning: nmap poppy.eh.codingliquids.com -p8000-9000 //TO SEARCH ports etween 8000 and 9000 //80 is defult port
5) Postman - Sending GET/POST requests with modified headers and authorisation tokens (https://github.com/fatihsencer/ctf.lib/tree/main/dCTF/web/secure_api)
6) Hashing - Tiger 128,4 - https://github.com/xxonorg/dCTF2021_Writeup/blob/main/Very%20Secure%20Website.md
    Magic Hashes (for PHP collisions where == is used instead of ===) - https://github.com/spaze/hashes
7) OWASP Juice Shop - https://github.com/bkimminich/juice-shop - For pentesting (insecure website)
8) Sublist3r (https://github.com/aboul3la/Sublist3r) - For finding subdomains
9) crt.sh - Another tool for subdomain enumeration
10) securityheaders.com - Analysis of HTTP headers on websites

## Rev
1) WORD document can have macros in it.
https://www.youtube.com/watch?v=Y7IJjnLGqTQ
Use oletools to extract macro (command: olevba -c word.docm)
