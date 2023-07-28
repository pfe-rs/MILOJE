### Modularni robot Miloje
Modularni Interfejs za Lansiranje Operativnih i Jednostavnih Ekstenzija

### Tema i cilj projekta
Implementacija modularnosti u masinskom, elektronskom i softverskom domenu robota.
* Masinski domen: Lako zamenjivi i sklopivi 3d modeli adaptera elektronskih komponenti
* Elektronski domen: Koriscenje elektronike koja je pogodna za dalje prosirenje projekta, tj. dodavanje modula
* Softverski domen: Programiranje elektronike na nacin koji omogucava sposobnost prilagodjavanja i dodavanja novih funkcija

### Komponente projekta
* Elektronske: 2 Nema 17 stepper motora, 2 servo motora, Arduino Mega, Arduino Mega Prototype Shield, Step down modul, 12V baterija, HC05 Bluetooth modul, ultrazvucni senzor
* Masinske: Aluminijumski profili(2*160 mm, 2*220 mm, 2*60 mm), 2 pogonska tocka, 1 balansirajuci tocak, drzaci stepper motora, adapteri za pogonske i balansirajuci tocak, dve platforme za postavljanje elektronike, pan\tilt platforma
* Softverske: Biblioteka sa klasama za serijsko upravljanje robotom (Bluetooth\UART), program za generisanje protokola komande

### Funkcionalnosti robota
* Bluetooth i UART komunikacija
* Funkcija pravolinijskog i krivolinijskog kretanja na osnovu zadatih parametara: broja obrtaja, brzine kretanja, ugla skretanja, distance skretanja
* Funkcija pokretanja servo motora (pan\tilt platforme)
* Funkcija ocitavanja merenja ultrazvucnog senzora
