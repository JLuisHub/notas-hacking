# Whitepages
xxd whitepages.txt | head

"Dos tipos de espacios, convertir un tipo en cero y el otro en binario, despues convertir el resultado de binario a ASCII" con el siguiente programa en python 

```python
from pwn import *
file = open('whitepages.txt','rb')
date = bytearray(file.read())
data = data.replace(b'\xe2\x80\x83',b'0')
data = data.replace(b'\x20,b'1')
data = data.decode('ascii')
data = unbits(data)
print(data)
```