# Level 27 -> level 28

## Objetivo

## Datos de acceso
Host: **bandit.labs.overthewire.org** on port 2220
Username: **bandit23**
Password: **YnQpBuifNMas1hcUFk70ZmqkhUU2EuaS**

## Solución
```bash
hone@Unidad03:~$ ssh bandit22@bandit.labs.overthewire.org -p 2220
```

```
bandit22@bandit.labs.overthewire.org's password: YnQpBuifNMas1hcUFk70ZmqkhUU2EuaS
```

```bash
bandit27@bandit:/tmp/rep$ git clone ssh://bandit27-git@localhost:2220/home/bandit27-git/repo
```

```
bandit27-git@localhost's password: YnQpBuifNMas1hcUFk70ZmqkhUU2EuaS
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```

```bash
bandit27@bandit:/tmp/rep$ cd repo/
```

```bash
bandit27@bandit:/tmp/rep/repo$ ls
README
```

```bash
bandit27@bandit:/tmp/rep/repo$ cat README 
The password to the next level is: AVanL161y9rsbcJIsFHuw35rjaOM19nR
```

## Notas adicionales
## Referencias