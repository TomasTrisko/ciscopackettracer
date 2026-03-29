# Model LAN v Cisco Packet Tracer

## Popis:
Tento projekt představuje funkční model lokální sítě v Cisco Packet Tracer. 
Topologie sítě se skládá ze dvou switchů (**S1, S2**) a čtyř koncových stanic (**PC1, PC2, PC3, PC4**). 

**Zapojení:**
- PC1 a PC2 jsou zapojeny do switche S1 přímým kabelem.
- PC3 a PC4 jsou zapojeny do switche S2 přímým kabelem.
- Switche S1 a S2 jsou propojeny kříženým kabelem.
- K nastavení switchů byl použit Laptop připojený konzolovým kabelem.

Všechny počítače mají statické IP adresy a masku podsítě. Komunikace napříč sítí je plně funkční, což dokazuje úspěšný ping z PC1 na PC4.

---
## Výpočet X

T = 84
R = 82
I = 73
S = 83
K = 75
O = 79

Součet: 84+82+73+83+75+79 = 476
X: 476 mod 256 = **220**

---
## Výpočet Y
T = 84
O = 79
M = 77
A = 65
S = 83

Součet: 84+79+77+65+83= 388
Výpočet Y: 388 mod 10 = **8**

Výsledek: 10.**220**.0.0 / **24**

---
## Sceenshoty z CPT

### 1. Laptop - nastavování switche
<img width="444" height="80" alt="Screenshot 2026-03-29 174939" src="https://github.com/user-attachments/assets/43481829-5563-428c-9c6e-725d64b139c7" />

### 2. PC1 - ipconfig
<img width="440" height="161" alt="Screenshot 2026-03-29 175147" src="https://github.com/user-attachments/assets/d503e961-52e8-473f-aa1c-486fe4f2b54e" />

### 3. PC1 - ping na PC4
<img width="397" height="194" alt="Screenshot 2026-03-29 175232" src="https://github.com/user-attachments/assets/07f41f8f-2271-4583-83dd-c6c69b3b1661" />











