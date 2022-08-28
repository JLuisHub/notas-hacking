# Level 8
## Objetivo
The password for the next level is stored in the file **data.txt** next to the word **millionth**

## Datos de acceso
Host: **bandit.labs.overthewire.org** on port 2220
Username: **bandit7**
Password: **HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs**

## Solución
**hone@Unidad03:~$** ssh bandit7@bandit.labs.overthewire.org -p 2220

bandit7@bandit.labs.overthewire.org's password: 
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

**bandit7@bandit:~$** ls
data.txt

**bandit7@bandit:~$** grep millionth data.txt 
millionth	cvX2JJa4CFALtqS87jk27qwqGhBM9plV

## Notas adicionales
## Referencias