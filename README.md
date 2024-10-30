# Objekt genkendelse med SOPAS engineering tool til SICK inspektor kammera
Programmet giver mulighed for at lave referance billeder med forskellige former, som cirkler og trekanter af forksellige størelser. 
Til at genkende et billede er der mulighder som objekt lokater, cirkel, egde tools, blob, patten, polygon, pixel counter, distance og angle.


## SICK Kammera specifikationer
- Mulighed af fokus instilling på selve kammeraet (manuelt)
- Tilslutnings muligheder af vspm-6f2113: Ethernet/IP
- Kun mulighed for 2D billede
- Billede frekevensrate 40 fps
- Arbejdsafstand	≥ 50 mm
- Arbejdsafstand med intern belysning	50 mm ... 200 mm
- Spektrum	Ca. 400 nm ... 750 nm
### EtherNet/IP™
Transmissionshastighed	100 Mbit/s

## Fordele og ulemper ved SICK på vores projekt 
### Ulemper
- 40 fps
- Langsom hastighed af kammera ved flere referance billeder
  
### Fordele
- Kammeraet har egen lys
- Spektrum	Ca. 400 nm ... 750 nm/altså hvad øjet kan se
- 2D billede

## Tilslutnings muligheder
- Ethernet/IP, TCP/IP OG webserver

24 volt DC
3 konfigurerbare outputs
4 defineret inputs

## Vores projekt
Vores projekt omhandler at finder en allankey på et fladoverflade og skulle kunne genkende forskellen på størlse og form af nøglen
### Guide 
1. Man starter programmet SOPAS enginering tool
2. først finder man kammeret herefter logger vi in på selve kammeraet med koden Inspector.
3. Derefter trykker man på edit for at komme ud af run så man kan indstille kammeraet.
4. Så skal man i image setting og trykke på auto for at kalibrere billedet
5. derefter skal vi gemme et referance objekt det gør vi ved at ligge vores objekt ind foran kammeraet og trykke på teach referance objekt
6. Så bruger funktionen objekt lokater og maker hele allan keyen på skærmen
7. Så bruger vi funktion distance 



