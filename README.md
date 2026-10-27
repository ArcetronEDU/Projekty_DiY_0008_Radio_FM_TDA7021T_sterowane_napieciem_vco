# Projekty_DiY_0008_Radio_FM_TDA7021T_sterowane_napieciem_vco
Materiały dodatkowe do filmów "Arduino to takie proste" (https://www.youtube.com/@arcetron)


Odświeżony projekt Radia FM TDA7021T, sterowny napięciem vco, wystarczy podłączyć w miejsce oznaczone sterownie: potencjometr 100K ohm
Jednak cel projektu jest aby wykorzystać stary analogowy układ radia FM współpracujący ze sterowaniem cyfrowym w oparciu o mikrokontroler i DAC
Przykładowo regulacja częstotliwością FM odbywa się z wykorzystaniem układu Attiny84A, potencjometru 10K i DAC: MCP4821E
Dzięki temu rozwiązaniu mamy płynny i cichy układ strojenia nawet jeśli jest znaczne zużycie potencjometru, ale sam fakt użycia DAC obniża zużycie potencjometru
i jednocześnie za pomocą programu można uzyskać dokładniejszy zakres strojenia, Cewka L2 z podanymi parametrami wyznacza lepszą czułość w zakresie: 88 - 98 Mhz 
Cewka za pinem 12 poprzez kondensator 68pF i cewkę daje dopasowanie anteny 75 ohm. Przy podłączeniu przewodu 50ohm należny zmienić kondensator na 100-120 pF i cewke z 5 zwojow na 4 zwoje 
aby nie było odbić stacji radiowych i przesterowania sygnału.

Uruchamianie:
Podczas pierwszego uruchamiania radia ustaw, potencjometr 100K w skrajnym położeniu w lewą stronę, na znaną Ci stacje radiową w okolicach 88-89MHz
reguluj kondensatorem strojeniowym aż usłyszysz dźwięk z radia. Cewka L1 powinna posiadać rdzeń i 3.5 zwojów, rdzeń powinien być ustawiony w środkowym połażeniu, na początku nie reguluj rdzeniem cewki tylko kondensatorem strojeniowym, kondensator C13 jest tylko opcją i nie jest wymagany, napięcie sterowania diodą warikap MV2105 jest wystarczające aby pokryć cały zakres pasma radiowego 88-108Mhz.

Projekt jest przetestowany i działa poprawnie . . . 


Pliki są w formacie wektorowym [.svg] i możesz je otworzyć i wydrukować używając programu: InkScape

Wszystkie grafiki są mojego autorstwa, możesz je pobrać i używać
© 2026 ARCETRON https://creativecommons.org/licenses/by-nc/4.0/legalcode.pl
Licencja: Creative Commons BY‑NC 4.0

Oznacza to, że:
- możesz kopiować, udostępniać i używać tej pracy za darmo,
- możesz ją modyfikować i tworzyć na jej podstawie własne materiały,
- musisz podać autora w sposób wskazany przez twórcę,
- nie wolno używać tej pracy w celach komercyjnych,
- nie wolno sprzedawać tej pracy ani wykorzystywać jej w płatnych projektach,
- jeśli publikujesz zmodyfikowaną wersję, również musisz podać autora oryginału,
- licencja nie ogranicza praw autora do komercyjnego wykorzystania własnej pracy. 
