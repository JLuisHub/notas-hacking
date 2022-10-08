# shark on wire 2

"Con whiresark snifear los paquetes desargados"
Observar el inicio y el final y convertir los puestors desde el inicio hasta el final de hexadecimal

o  

el siguiente script en python

```python
fomr scapy.all import *
packets = rdpcap('capture.pcap')
flag=''
for p in packets:
    if UDP in p and p[UDP].dport==22:
        if p[UDP].sport > 5000:
            flag+=chr(p[UDP].sport-5000)
print(flag)
```