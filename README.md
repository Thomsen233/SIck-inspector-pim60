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
<img src="(https://github.com/user-attachments/assets/e9f77fc7-d8ca-43d6-bc3b-015cb073ab4b" width="600">

1. Man starter programmet SOPAS enginering tool

<img src="https://github.com/user-attachments/assets/35a2ec15-dfc1-4ab8-96a3-7fc298d047b6" width="600">

3. først finder man kammeret herefter logger vi in på selve kammeraet med koden Inspector.
4. Derefter trykker man på edit for at komme ud af run så man kan indstille kammeraet.
   
<img src="https://github.com/user-attachments/assets/16af90a8-6ec2-4318-8ddd-4b66e3d46058" width="600">

6. Så skal man i image setting og trykke på auto for at kalibrere billedet
   
<img src="https://github.com/user-attachments/assets/9834ade8-70c5-416d-b9b8-480954ddc9ee" width="600">

8. derefter skal vi gemme et referance objekt det gør vi ved at ligge vores objekt ind foran kammeraet og trykke på teach referance objekt
   
<img src="https://github.com/user-attachments/assets/b26d9610-4c0b-431c-9b1d-6148bc4737c1" width="600">

10. Så bruger funktionen objekt lokater og maker toppen af allan keyen på skærmen
    
<img src="https://github.com/user-attachments/assets/29b9b31b-03a4-41ce-a21a-e660a82a2074" width="600">

12. Så bruger vi funktionen pixel counter for at makere hvor langt skaftet er på allan keyen
13. I menuen til højre under tools skal vi makere objekt lokater, så ændre vi på egde contrast indtil vi har mekeret hele vejden rundt til toppen allan keyen
14. Så vælger vi pixel counter under tools, der ændre vi på intesity range indtil hele skaftet er makeret markant gul.
15. efter det skal vi ændre på resolve and tolerances for at ændre om vores objekt skal være failed eller passed
   






