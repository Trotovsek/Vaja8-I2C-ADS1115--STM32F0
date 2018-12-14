# Vaja8-I2C-ADS1115-STM32F0
STM preko I2C komunikacije komunicira s ADS1115, ki bere 4 analogne vrednost
CubeMX
c) V pinout zavihku omogočite I2C komunikacijo. Kateri pini se aktivirajo? PB9 in PB8. Koliko različnih
I2C komunikacij vaša razvojna plošča omogoča? 2 .
e) Sedaj ADS1115 modul povežite z ustreznimi pini na STM32F0. Katere pine ste izbrali? Dopolnite tabelo:
ADS 1115:      STM32F0: 
SCL             PB8
SDA             PB9
ADDR            GND
ALRT            /
VDD             5v

f) V zavihku Configuration kliknite na I2C gumb in spremenite hitrost na 400 kHz. Kaj ste izbrali? Fast mode.


Kyle 
b) Pretvorite binarni naslov 1001000 v šastnajstiškega: 48 HEX.

e) ADS pretvorniku moramo programsko nastaviti vhodno ojačanje (programmable gain amplifier
configuration). Ker so naše vrednosti na potenciometru do 5 V, moramo ustrezno postaviti 16 bitni
register - bite od 11:9 postavimo na 000, zato je max. napetost ± 6.144V. (glej PDF, str. 19).
