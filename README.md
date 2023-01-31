# **Task 1** 

## **Subtask 1** 

6 punktów 


## **Subtask 3** 

Hej :) Mam na imię Justyna. Jestem osobą ambitną, łatwo nawiązującą kontakty i wychodzącą naprzeciw potrzebom innych. Lubię sprawdzać siebie i różne rozwiązania, a nauka nowych rzeczy sprawia mi przyjemność.


Aktualnie z braku satysfakcji zawodowej postanowiłam zmienić ścieżkę mojej kariery. Jakiś czas temu zaciekawił mnie temat testowania oprogramowania i zaczęłam pogłębiać swoją wiedzę w tej dziedzinie. Na facebooku wyświetliła mi się reklama Waszego projektu i postanowiłam z Waszą pomocą stworzyć portfolio, które pomoże mi w rozpoczęciu praktyki testerskiej i sprawdzeniu czy jest to praca dla mnie.


__*Justyna*__ 


## **Subtask 4** 

__Zrobiony przy uzyciu konta user01@getnada.com__

* Na czym polega ta aplikacja? Do czego służy?

Aplikacja jest przeznaczona dla "łowców talentów" skautów piłki nożnej. Służy do przeglądanie wskaźników, umiejętności i pozycji zawodników z różnych klubów. Użytkownik ma możliwość sprawdzenia imienia, nazwiska, wieku, zajmowanej pozycji, przynależności do klubu, sprawdzenia ilości raportów oraz meczy i punktowej recenzji.


* Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)

Aplikacja umożliwia dodawania zawodników. Wyświetlania listy zawodników, oraz edycji dodanych już piłkarzy. Mamy też możliwość filtrowania.

Nie dokońca są te funkcjonalności intuicyjne. Nie ma możliwości wyboru ilu zawodników chcemy mieć na jednej stronie. Nie ma możliwości filtrowania przez dominującą nogę, osiągnięcia oraz alternatywną pozycję zawodnika.

Brak wyrażnego podziału na kolumny.


* Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

Interfej aplikacji mi się nie podoba. Wygląda jak schemat, a nie gotowa aplikacja. Wygląd aplikacji nie jest czytelny, a zakładki są dziwnie rozmieszczone. Moim zdaniem powinny one być w poziomie, a nie w pionie. Layout jest też za szeroki, więkość aktualnych aplikacji układana jest w środkowej części.

* Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).

Nie miałam problemu ze znalezieniem formularza dodawania nowego zawodnika piłki nożnej do systemu, ale moim zdaniem znajduje się on w dziwnym miejscu. Powinien znajdować się przy zakładach, a nie tylko na stronie głównej. Ponadto powinno się to właśnie nazywać formularz, a nie linki pomocnicze.

W filtrach brakuje pół wyborów w skończonych kategoriach np. pozycje zawoników są już określone, a w tej aplikacji jest możliwość wpisywania "czegokolwiek".


* Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)

  * Brak identyfikacji ID dla poszczególnych zawodników w zakładce _Gracze_
  * Możliwość wpisania imienia i nazwiska składającego się ze znaków, cyfr, zbyt krótkich lub "hasłowych"
  * Brak wartości brzegowych wieku zawodników, czyli możliwość wpisania wieku na minusie, a także zbyt dużych (w rzeczywistosci najstarszy piłkarz ma 55 lat, a najmłodszy 16 lat)
  * Brak wartości brzegowych dla wagi i wzrostu - jest możliwość wpisania wartości na minusie, liter lub nieprawdopodobnych wartości
  * Możliwość dodania nieistniejących pozycji zawodników
  * Możliwość dodania nieistniejących klubów
  * Brak ograniczenia w ilości znaków w poszczególnych kolumnach
  * W filtrach w wersji polskiej mamy język angielski pomieszany z językiem polskim, problem ten też jest przy dodawaniu gracza (znowu w języku angielskim Required w polskiej wersji aplikacji)
  * Przy przechodzeniu przez poszczególne strony w zakładce _Gracze_ zmienia się pozycja kolumn
  * Przy przechodzeniu przez poszczególne strony w zakładce _Gracze_ okno ma możliwość rozciąga się (brak zwijania długich nazw)
  * Możliwość dodawania tych samych zawodników
  * Przy eksporcie do .csv wyskakują błedy w dwóch ostatnich kolumnach
  * Przy eksporcie do .csv w kolumnie wiek wpisane są daty, a w aplikacji tylko wiek
  * Nie można zaznaczyć więcej zawodników niż znajduje się na jednej stronie
  * Przy wyborze drukowania nie zawsze zawsze pojawiają się linie oddzielające użytkowników
  * Możliwość wpisania w pole profil Facebook, Łączy nas piłka i 90 minut linku nie z tych aplikacji lub w ogóle brak linku (wpisane są dowolne znaki)
  * Przy dodawaniu nowego gracza pomimo, iż z * (czyli wymagane jest zaznaczone imię, nazwisko, data urodzenia oraz główna pozycja) to przy próbie zapisu na czerwono podświetlone tylko imię - mamy kod 400 (POST) 
  * Błędne wyświetlanie komunikatów - wyskakuje nam w http, że musimy dodać email, ale to pole nie jest podświetlane na czerwono, ani nie ma *
  * Bug - kod błędu 404 (strona łączy się z serwerem, ale nie może znaleść właściwego pliku odpowiadającego za działanie danej podstrony) https://scouts-test.futbolkolektyw.pl/pl/favicon.ico
  * Bug - Params `start` and `limit` are deprecated. Use `_start` and `_limit`, który nie wiem co oznacza dotyczy rozszerzenia js i znajduje się w zakładce players
  * Brak możliwości dodawania graczy z innych krajów
  * Brak zabezpieczeń przed zmianami - zmian może dokonać każdy użytkownik, nie tylko administrator lub dany zawodnik
  * Brak przycisku na banerze przenoszącego na główną stronę - jest to bardzo niewygodne zwłaszcza przy obsłudze na aplikacjach mobilnych
  * Na aplikacjach mobilnych, żeby zmienić zakładkę musimy wciskać hamburger menu, co jest czasochłonne
  * Niewygodne przeglądanie zakładki _Gracze_ na apliacji mobilnej


# **Task 2** 

## **Subtask 1** 

[Google exel file with Subtask 1](https://docs.google.com/spreadsheets/d/1GCCXNPcKsoPUBCMYPSMUOpLdvg_PyNnJ/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)

## **Subtask 2** 

[Google exel file with Subtask 2](https://docs.google.com/spreadsheets/d/1AAmcIa7zSUd9py2PaPOrjbgemBezKZJ3/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)


## **Subtask 3** 

*Po co piszemy test case’y?*

Warto pisać przypadki testowe, ponieważ jest to dobry sposób na spisanie wiedzy na temat testowanej aplikacji/systemu. Przypadki testowe pomagają w trakcie testowania poprawności oprogramowania, ponieważ porządkują pracę. Dzięki czemu wiadomo, ile funkcjonalności jeszcze zostało nam do przetestowania. Dobry przypadek testowy powinien odpowiadać na pytanie: __„Co tak naprawdę chcę przetestować?”__ Ponadto po zakończeniu testów, na podstawie przypadków testowych tester może tworzyć raporty z wykonanych testów na danej aplikacji/systemie.

## **Subtask 4** 

[Google exel file with Subtask 4](https://docs.google.com/spreadsheets/d/1y0K49Haq27BUf7IkJgaE6jj7aj6kVhOM/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)

# **Task 3** 

## **Subtask 1** 

[Google exel file with Subtask 1  - Bug file](https://drive.google.com/drive/folders/1JixfAMyjrwzN8rfYeg_LuM0dOhTPa_kA?usp=share_link)

## **Subtask 2** 

[Google exel file with Subtask 2  - Bug reports](https://docs.google.com/spreadsheets/d/1uu-Nfliq6UwBACkz586v2ltJNb2WSb_q/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)


## **Subtask 3** 

[Subtask 3 -Bug Tracker](https://docs.google.com/spreadsheets/d/15diIoCJH5uVvKA3STjQALmZZoe-7LPNg1GsM2xaEkdw/edit?usp=share_link)
