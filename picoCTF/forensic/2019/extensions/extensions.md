# extensions
## Objetivo
This is a really weird text file [TXT](https://jupiter.challenges.picoctf.org/static/e7e5d188621ee705ceeb0452525412ef/flag.txt)? Can you find the flag?

## Solución
```bash
hone@Unidad03:~/extensions$ file flag.txt 
flag.txt: PNG image data, 1697 x 608, 8-bit/color RGB, non-interlaced
```

```bash
hone@Unidad03:~/extensions$ file flag.txt 
flag.txt: PNG image data, 1697 x 608, 8-bit/color RGB, non-interlaced
```

```bash
hone@Unidad03:~/extensions$ open flag.png
```

Se abre una imagen con la bandera.

Bandera: *picoCTF{now_you_know_about_extensions}*

## Referencias