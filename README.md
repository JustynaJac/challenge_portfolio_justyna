# **Task 1** 

## **Subtask 1** 

6 punktów 


## **Subtask 3** 

Hej :) Mam na imię Justyna. Jestem osobą ambitną, łatwo nawiązującą kontakty i wychodzącą naprzeciw potrzebom innych. Lubię sprawdzać siebie i różne rozwiązania, a nauka nowych rzeczy sprawia mi przyjemność.


Z powodu aktualnego braku satysfakcji zawodowej postanowiłam zmienić ścieżkę mojej kariery. Jakiś czas temu zaciekawił mnie temat testowania oprogramowania i zaczęłam pogłębiać swoją wiedzę w tej dziedzinie. Na facebooku wyświetliła mi się reklama Waszego projektu i postanowiłam z Waszą pomocą stworzyć portfolio, które pomoże mi w rozpoczęciu praktyki testerskiej i sprawdzeniu czy jest to praca dla mnie.


__*Justyna*__ 


## **Subtask 4** 

__Zrobiony przy uzyciu konta user01@getnada.com__

* Na czym polega ta aplikacja? Do czego służy?

Aplikacja jest przeznaczona dla "łowców talentów" skautów piłki nożnej. Służy do przeglądanie wskaźników, umiejętności i pozycji zawodników z różnych klubów. Użytkownik ma możliwość sprawdzenia imienia, nazwiska, wieku, zajmowanej pozycji, przynależności do klubu, sprawdzenia ilości raportów oraz meczy i punktowej recenzji.


* Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)

Możliwość dodawania zawodników. Wyświetlania listy zawodników, oraz edycji dodanych już piłkarzy. Mamy też możliwość filtrowania.

Nie dokońca są te funkcjonalności intuicyjne. Nie ma możliwości wyboru ilu zawodników chcemy mieć na jednej stronie. Nie ma możliwości filtrowania przez dominującą nogę, osiągnięcia oraz alternatywną pozycję zawodnika.

Nie rozumiem pól Łączy nas piłka i 90 minut.

Brak podziału na kolumny.


* Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

Interfej aplikacji mi się nie podoba. Wygląda jak schemat, a nie gotowa aplikacja. Jest zrobiona w starym stylu modnym w latach 2000-ych.

* Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).

Nie miałam problemu ze znalezieniem formularza dodawania nowego zawodnika piłki nożnej do systemu, ale moim zdaniem znajduje się on w dziwnym miejscu. Ponadto powinno się to właśnie nazywać formularz, a nie linki pomocnicze.

W filtrach powinniśmy również mieć możliwość przefiltrowania wieku, pozycji, klubu, ilości meczów itp. a nie mieć tylko możliwość dodawania.


* Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)

  * Brak identyfikacji ID dla poszczególnych zawodników
  * Możliwość wpisania imienia i nazwiska składającego się ze znaków, cyfr, zbyt krótkich lub "hasłowych"
  * Brak wartości brzegowych wiekowych zawodników, czyli możliwość wpisania wieku na minusie, a także zbyt dużych (najstarszy piłkarz ma 55 lat, a najmłodszy 16 lat)
  * Brak wartości brzegowych dla wagi i wzrostu jest możliwość wpisania wpisania wieku na minusie, oraz liter
  * Możliwość dodania nieistniejących pozycji zawodników
  * Możliwość dodania nieistniejących klubów
  * Brak ograniczenia w ilości znaków w poszczególnych kolumnach
  * W filtrach w języku polskim mamy język angielski pomieszany z językiem polskim
  * Przy przechodzeniu przez poszczególne strony w zakładce _Gracze_ zmienia się pozycja kolumn
  * Przy przechodzeniu przez poszczególne strony w zakładce _Gracze_ okno ma możliwość rozciąga się w przeglądarce mozilla w chromie już nie
  * Możliwość dodawania tych samych zawodników
  * Przy eksporcie do .csv wyskakują błedy w dwóch ostatnich kolumnach
  * Przy eksporcie do .csv w kolumnie wiek wpisane są daty, a w aplikacji tylko wiek
  * Nie można zaznaczyć więcej zawodników niż znajduje się na jednej stronie
  * Przy wyborze drukowania nie zawsze zawsze pojawiają się linie oddzielające użytkowników
  * Możliwość wpisania w pole profil facebook linku nie z tej aplikacji
  * Przy dodawaniu nowego gracza pomimo, iż z * (czyli wymagane jest zaznaczone imię,nazwisko, data urodzenia oraz główna pozycja) to przy zapisywaniu na czerwono pojawia się tylko imię i znowu w języku angielskim Required w polskiej wersji Podświetlone tylko imię, a powinno również być nazwisko i błędne wyświetlanie komunikatów. Mamy kod 400 (POST) dodania
  * Kolejnym błędem tutaj jest to, że  wyskakuje nam w http, że musimy dodać email ale nie podświetla się to na czerwono.
  * Bug kod błędu 404 (strona łączy się z serwerem, ale nie może znaleść właściwego pliku odpowiadającego za działanie danej podstrony) https://scouts-test.futbolkolektyw.pl/pl/favicon.ico
  * Bug - Params `start` and `limit` are deprecated. Use `_start` and `_limit`, który nie wiem co oznacza dotyczy rozszerzenia js i znajduje się w zakładce players
  * Brak możliwości dodawania graczy z innych krajów
  * Brak zabezpieczeń przed zmianami - zmian może dokonać każdy użytkownik, nie tylko administrator lub zawodnik
