# Level 9
## Objetivo
The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once

## Datos de acceso
Host: **bandit.labs.overthewire.org** on port 2220
Username: **bandit7**
Password: **cvX2JJa4CFALtqS87jk27qwqGhBM9plV**

## Solución
**hone@Unidad03:~$** ssh bandit8@bandit.labs.overthewire.org -p 2220

bandit8@bandit.labs.overthewire.org's password: 
cvX2JJa4CFALtqS87jk27qwqGhBM9plV

**bandit8@bandit:~$** ls
data.txt

**bandit8@bandit:~$** sort data.txt | uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

## Notas adicionales
## Referencias
[Piping and Redirection](https://ryanstutorials.net/linuxtutorial/piping.php)