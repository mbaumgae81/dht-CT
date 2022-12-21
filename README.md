dht-CT
======

Quellcode zum auslesen des DHT 11 Sensors am Cubietruck mit den GPIO´s


DHT 11 Sensor Auslesen

###Kompilieren
gcc dht.c -c
gcc gpio_lib.h -c
gcc dht.o gpio_lib.o -o dht

##Ausführen
#./dht 11
Data (40): 0x22 0x0 0x17 0x0 0x39
Temp = 23 *C, Hum = 34 %
