<h1>HTB WriteUp</h1>
![logo](https://www.hackthebox.eu/images/logo600.png)
<h1>Hi, There.</h1>

This is my own page for Hack The Box Write Up

RULES :

1.For decrypting .PDF password, AFTER Traceback machine 
- LINUX MACHINE : cat /etc/shadow

  Hash Format :

  root:<b>$6$.n.</b>:17736:0:99999:7:::

- WINDOWS MACHINE : install hashdump.exe on the machine and convert the hash to md5

  Hash Format:

  Administrator:500:aad3b435b99999eeaad3b123b51404ee:31d6cfe0doekjd31b73c59d7e0c:::

  echo Administrator:500:aad3b435b99999eeaad3b123b51404ee:31d6cfe0doekjd31b73c59d7e0c::: | md5sum

  <b>66ad58ccde4cb2e0dac83944f85229c3</b>

2.Before Traceback machine use ROOT FLAG as .PDF Password

3.if the machine is active so the writeup still protected

4.if the machine already retired, the password will be removed.



ps. i'm still a n3wb :(
YouTube : https://www.youtube.com/watch?v=ux3cPwC507U&list=PLIJsl6YfUBxEJL4E60BpGXpJ52vdmANPh
