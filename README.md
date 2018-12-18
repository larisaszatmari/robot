ID	Description
SysRs_1.	Proiectul foloseste  senzori ultrasonici pentru distanta HC-SR04 si un senzor ultrasonic pentru distanta HC-SR04+.
SysRs_2.	Proiectul foloseste 2 motoare de curent continu fara peri .
SysRs_3.	Proiectul contine un driver de motor L298N.
SysRs_4.	Robotul foloseste 4 roti pentru deplasare.
SysRs_5.	Proiectul contine un Breadbord pentru a putea face conexiunea intre placa Arduino si driver de motor (L298N).
SysRs_6.	Controlul se face printr-o placuta Arduino Nano 
SysRs_7.	Tensiunea de intrare pentru placuta Arduino Nano este de +5V.
SysRs_8.	Tensiunea de intrare pentru driver-ul de motor este de +5V.
SysRs_9.	Robotul trebuie sa gaseasca gasirea dintr-un labirint folosind informatiile primite de la senzori.
SysRs_10.	Fiecare senzor: stanga , dreapta , fata masoara o distanta ,iar robotul se deplaseaza in directia in care distanta fata de obstacol este mai mare .
SysRs_11.	Daca distanta masurata de senzorii : stang, drept , fata e egala , atunci robotul face un pas inapoi.
HW_1.	 
HW_2.	Conexiunea intre componente se realizeaza cu fire mama-mama, tata-tata, mama-tata.
SW_1.	sonar.ping([max_cm_distance]) trimite un ping și obțineți timpul de intoarcere al sunetului (în microsecunde) ca rezultat. [max_cm_distance]  va permite  , opțional ,setarea unei  distanțe maxima noua.
SW_2.	sonar.ping_in([max_cm_distance]) trimite un ping și obțineți distanta in iches numar intreg. [max_cm_distance] va permite  , opțional ,setarea unei  distanțe maxima noua.

SW_3.	sonar.ping_cm([max_cm_distance]) trimite un ping și obțineți distanța în centimetri numar intreg. [max_cm_distance]  va permite  , opțional ,setarea unei  distanțe maxima noua.
SW_4.	sonar.ping_median(iterations, [ max_cm_distance])trimite mai multe pinguri (default=5), elimina valorile inafara intervalului ,calculeaza valoarea mediana,  va permite  , opțional ,setarea unei  distanțe maxima noua.
SW_5.	sonar.convert_in(echoTime)  converteste echoTime de la microsecunde la inches.
SW_6.	sonar.convert_cm(echoTime) converteste echoTime de la microsecunde la centimetric.
SW_7.	sonar.ping_timer(function, [ max_cm_distance]) trimite o un ping si apeleaza o functie care testeaza  dacă ping-ul este complet. [max_cm_distance] ]  va permite  , opțional ,setarea unei  distanțe maxima noua.
SW_8.	sonar.check_timer() verifica dacă ping-ul sa întors în limita de distanță stabilită.
SW_9.	NewPing::timer_us(frequency, function) apeleaza funcția la fiecare interval de timp dat ca parametru in microsecunde.
SW_10.	NewPing::timer_ms(frequency, function) apeleaza funcția la fiecare interval de timp dat ca parametru in milisecunde.
SW_11.	NewPing::timer_stop() opreste timpul.



