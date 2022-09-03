# Level 3 -> level 4

## Objetivo
The password for the next level is stored in a hidden file in the **inhere** directory.

## Datos de acceso
Host: **bandit.labs.overthewire.org** on port 2220
Username: **bandit3**
Password: **UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK**

## Solución
**hone@Unidad03:~$** ssh bandit3@bandit.labs.overthewire.org -p 2220

bandit3@bandit.labs.overthewire.org's password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

**bandit3@bandit:~$** ls
inhere

**bandit3@bandit:~$** cd inhere/

**bandit3@bandit:~/inhere$** ls -la
total 12
drwxr-xr-x 2 root    root    4096 May  7  2020 .
drwxr-xr-x 3 root    root    4096 May  7  2020 ..
-rw-r----- 1 bandit4 bandit3   33 May  7  2020 .hidden

**bandit3@bandit:~/inhere$** cat .hidden 
pIwrPrtPN36QITSp3EQaw936yaFoFgAB

## Notas adicionales
## Referencias