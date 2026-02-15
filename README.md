Bună ziua, urmați pașii pentru a face un atac ddos ​​pe o rețea wi-fi
1) primul pas aveți devoie de un sistem de tip Linux
kali-linux

ubuntu

linux mint

fredora

blacktrack r3

Parrot 

și altele care le mai cunoașteți

2)pasul doi instalați sistemul pe un dispozitiv sau mașină virtuoală

deschideți terminalul consolei, scrieți comanda sudo airmon-ng

Inportat aveti devoie de un adapter usb wifi care acceptă monitorizarea rețelei în zona în care vă aflați

<img width="1920" height="1080" alt="Screenshot_2023-12-16_17_22_29" src="https://github.com/user-attachments/assets/eaf9ab38-6458-443f-90f2-6064985717da" />

3)pasul trei scrieți in consolă comanda următoarea 

(sudo airmon-ng wlan0) pentru a activa adaptorul de monitorizare

! wlan0 asta e numele la interfața la adapterul dvs la dvs poate fi deferit numele 

4) pasul patru (sudo airmon-ng wlan0 start) pentru a activa adaptorul de monitorizare
5) <img width="1920" height="1080" alt="Screenshot_2023-12-16_17_23_26" src="https://github.com/user-attachments/assets/5ad19ce8-4557-4b84-8b5c-06d61ef86736" />
5)pasul cinci Scrieți comanda (sudo airmon-ng) pentru a vedea dacă adaptorul a fost activat pentru monitorizare, când adaptorul a fost activat în modul de monitorizare, apoi își schimbă numele din wlan0 în wlan0mon, de exemplu în cazul dvs. pot fi alte caractere ale numelui ca în imagine

 6)pasul șase Scrieți comanda (sudo airodump-ng wlan0mon)pentru a scana rețelele din zonă, așa cum se arată     în imagine
<img width="1920" height="1080" alt="Screenshot_2023-12-16_17_25_26" src="https://github.com/user-attachments/assets/b5392aaf-5281-4839-a74a-a79c8c42dd13" />
<img width="1920" height="1080" alt="Screenshot_2023-12-16_17_25_50" src="https://github.com/user-attachments/assets/35ef770f-1248-42bf-843c-24586fdeb626" />

7pasul șapte Scrieți comanda (sudo airodump--channel) acesta este canalul de rețea pe care să-l atacați --bssid adresa MAC-OS a rețelei pe care să vă ajute să o atacați numele interfeței adaptorului wlan0mon apăsați enter exemplul de imagine de mai jos.
<img width="1920" height="1080" alt="Screenshot_2023-12-16_17_27_37" src="https://github.com/user-attachments/assets/ee20362d-beb2-4e79-9e57-1e15b269decd" />
<img width="1920" height="1080" alt="Screenshot_2023-12-16_17_28_09" src="https://github.com/user-attachments/assets/3e4f0ff5-6075-4d0f-83cb-e8e4c9bbe0da" />

8) pasul opt Scrieți comanda sudo aireplay-ng --deauth 8000 acesta este cât de mult trafic doriți să trimiteți atacul către ținta pe care ați ales-o --bssid  aceasta este adresa MAC-OS a rețelei pe care ați ales să o atacați wlan0mon numele interfeței la adaptor apăsați enter
<img width="1920" height="1080" alt="Screenshot_2023-12-16_17_31_54" src="https://github.com/user-attachments/assets/5b2d98be-4534-4062-b726-3243c345b038" />
   <img width="1920" height="1080" alt="Screenshot_2023-12-16_17_32_03" src="https://github.com/user-attachments/assets/703c361e-4a99-48b1-bd9a-4d0271651f2b" />


   !Acum rețeaua este blocată și nimeni nu se poate conecta la rețea prin WI-FI (WLAN)

   !INPORTAT BLOCARE E DOAR PRIN WLAN PRIN LAN NU ESTE

   WLAN => CONECTARE PRIN WI-FI
   LAN => CONECTARE PRIN CABLU UTP => RJ45

                                         !
                                   ANUNȚ INPORTAT
                           ACEST ESTE FOLOSIT IN SCOPURI BUNE 
                           NU FOLOSITI ILEGAL CĂ ESTE PEDEPSIT CONFORM LEGI IN VIGOARE
                           PE PROPEA RĂSPUNDE SE FOLOSESTE

                       

   

