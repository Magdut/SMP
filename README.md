# SMP
Robot
Roboțelul reprezintă o mașinuța care se poate plimba prin camera fără a se lovi de diversele obstacole. In continuare, ea poate fi upgdatata pentru diverse 
functioloanitati.
Aceasta este alcătuită dintr-o placa de plastic de care se prind doua roti de mașinuța cu motor DC( adică poate conversti curentul DC electric in energie mecanica
pentru acționarea roților). In fata are o roata de tip cărucior care ii oferă mobilitate și din păcate ii scade din precizia Mișcării. 
Roboțelul conține și un senzor ultrasonic,care trimite un echo la o distanta de maximum 2 metri, si asteapta sa se intoarca pentru a determina distanta fata de obiect,
ea fiind transpusa in cm in cod.

Mai are un servomotor( care implica poziții relative reglabile între anumite componente reglabile ) sub senzorul ultrasonic care el fizic nu merge si care ar fi trebuie
sa invarta senzoru si sa ii ofere o miscare de tip eagle eye(asa e in tehnica- cum se mișcă radarul). Daca este mișcat  stanga dreapta de senzoru ultrasonic
( dar  cu grija )se misca putin si face si zgomotul ala de motoras.

Pe suportul de plastic se mai afla și arduino Uno pe care a fost pus codul in care este definita fiecare miscare (stanga dreapta fata spate) si se da tensiune pe anumiti pini

Pentru ca tot sistemul sa meargă, a fost necesara o baterie de 9V

