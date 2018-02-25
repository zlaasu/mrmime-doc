=================
@Mr mime dla opornych/krok po kroku/w weekend – niepotrzebne skreślić 😊
=================

Mr mime to bot do otrzymywania spersonalizowanych wiadomości o pokemonach z map zlasu.org. **Aby zacząć**, otwórz prywatną wiadomość do @mr mime i pisz.

Komenda: ::

  !help
  
*Wypisze komendy, które można wykorzystać.*


**Dodawanie pokemonów** wykonuje się za pomocą komendy: ::

  !addpokemon <pokemon list> <miniv,maxiv> <mincp,maxcp> <minlvl,maxlvl> <location list>

W tej komendzie każdy z filtrów, oprócz lokacji, jest opcjonalny (bez podania lokacji komenda nie zostanie przyjęta). 

**Przykłady użycia:** ::

  !addpokemon lapras warszawa  
*...powiadomienia o laprasach w obszarze warszawa.*

::

  !addpokemon lapras 20 warszaw 
  !addpokemon lapras 20iv warszawa
*...powiadomienia o laprasach z iv ≥ 20% w obszarze warszawa.*

::

  !addpokemon lapras <10, 20> warszawa
  !addpokemon lapras <10iv, 20iv> warszawa
*...powiadomienia o laprasach z iv z przedziału 10-20% w obszarze warszawa.*

::

  !addpokemon lapras 20cp warszawa
*...powiadomienia o laprasach z cp ≥ 20 w obszarze warszawa.*

::

  !addpokemon lapras lvl20 warszawa
*...powiadomienia o laprasach z lvl ≥ 20 w obszarze warszawa.*

::

  !addpokemon lapras <10cp, 2000cp> warszawa
*...powiadomienia o laprasach z cp z przedziału 10-2000 w obszarze warszawa.*

::

  !addpokemon lapras <10iv, 20iv> <10cp, 20cp> warszawa
*...powiadomienia o laprasach z iv z przedziału 10-20% i cp z przedziału 10-20 w obszarze warszawa.*

::

  !addpokemon lapras <10iv, 20iv> <10cp, 20cp> <lvl5, lvl15> warszawa
*...powiadomienia o laprasach z iv z przedziału 10-20% i cp z przedziału 10-20 o poziomie z zakresu 5-15 w obszarze warszawa.* 

::

  !addpokemon <lapras, eevee, bagon> <warszawa, podkowa>
*...powiadomienia o 3 wybranych poksach w dwóch wybranych obszarac.*






