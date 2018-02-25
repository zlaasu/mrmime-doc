=================
Rajdy
=================

Możesz dostawać powiadomienia o pojawieniu się określonego pokemona (lub jajka określonego poziomu trudności) w rajdzie w danym gymie lub we wszystkich gymach z określonego obszaru.

Dodawanie rajdu do powiadomień wykonuje się za pomocą komendy: ::

  !addraid <pokemon list> <gym name> <location list>
  
Należy podać pokemony i lokację. 

------------

Poniżej przykłady użycia:

::

  !addraid lapras warszawa
  
...powiadomienia o laprasach w rajdach obszarze warszawa.

::

  !addraid <lapras, rayquaza> <warszawa, podkowa>
  
...powiadomienia o laprasach i rayquazach w rajdach obszarach warszawa i podkowa.

::

  !addraid lapras <WKD Podkowa Leśna Główna> podkowa
  
...powiadomienia o laprasach w rajdzie dla gymu - WKD Podkowa Leśna Główna, obszar podkowa – zawsze trzeba podać obszar, w którym znajduje się gym.

::

  !addraid egglvl5 <WKD Podkowa Leśna Główna> podkowa
  
...powiadomienia o jajkach o poziomie trudności 5 dla gymu - WKD Podkowa Leśna Główna, obszar podkowa – zawsze trzeba podać obszar, w którym znajduje się gym.

::

  !addraid egglvl5 <WKD Podkowa Leśna Główna> podkowa
  
...powiadomienia o jajkach o poziomie trudności 5 dla gymu - WKD Podkowa Leśna Główna, obszar podkowa – zawsze trzeba podać obszar, w którym znajduje się gym.

::

  !addraid <egglvl1, egglvl5> <podkowa, warszawa>
  
...powiadomienia o jajkach o poziomie trudności 1 i 5 dla gymów z obszarów warszawa i podkowa.

---------------------

Usuwanie pojedynczych powiadomień – **DOKŁADANIE ta sama konfiguracja** poprzedzona komendą **!delraid** np.: ::

  !delraid lapras <WKD Podkowa Leśna Główna> podkowa
  
Usuwanie wszystkich powiadomień dodanych przez !addraid ::

  !resetraid




