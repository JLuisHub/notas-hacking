# Level 6 -> level 7

## Objetivo
The password for the next level is stored **somewhere on the server** and has all of the following properties:

-   owned by user bandit7
-   owned by group bandit6
-   33 bytes in size

## Datos de acceso
Host: **bandit.labs.overthewire.org** on port 2220
Username: **bandit6**
Password: **P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU**

## Solución
```properties
hone@Unidad03:~$ ssh bandit6@bandit.labs.overthewire.org -p 2220
```

```properties
bandit6@bandit.labs.overthewire.org's password: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
```

```properties
andit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
```

```properties
andit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password 
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
```

## Notas adicionales
## Referencias
[What Is /dev/null in Linux?] (https://www.maketecheasier.com/dev-null-in-linux/)