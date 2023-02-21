# **Task 1** 

## **Subtask 1** 

6 punktów :baby_chick:


## **Subtask 3** 

Hej :wave: Mam na imię Justyna. Jestem osobą ambitną, łatwo nawiązującą kontakty i wychodzącą naprzeciw potrzebom innych. Lubię sprawdzać siebie i różne rozwiązania, a nauka nowych rzeczy sprawia mi przyjemność.


Aktualnie z braku satysfakcji zawodowej postanowiłam zmienić ścieżkę mojej kariery. Jakiś czas temu zaciekawił mnie temat testowania oprogramowania i zaczęłam pogłębiać swoją wiedzę w tej dziedzinie. Na facebooku wyświetliła mi się reklama Waszego projektu i postanowiłam z Waszą pomocą stworzyć portfolio, które pomoże mi w rozpoczęciu praktyki testerskiej i sprawdzeniu czy jest to praca dla mnie.


*Justyna* :smiley:


## **Subtask 4** 

__Zrobiony przy uzyciu konta user01@getnada.com__

:white_square_button: *Na czym polega ta aplikacja? Do czego służy?*

Aplikacja jest przeznaczona dla "łowców talentów" skautów piłki nożnej. Służy do przeglądanie wskaźników, umiejętności i pozycji zawodników z różnych klubów. Użytkownik ma możliwość sprawdzenia imienia, nazwiska, wieku, zajmowanej pozycji, przynależności do klubu, sprawdzenia ilości raportów oraz meczy i punktowej recenzji.


:white_square_button: *Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)*

Aplikacja umożliwia dodawania zawodników. Wyświetlania listy zawodników, oraz edycji dodanych już piłkarzy. Mamy też możliwość filtrowania.

Nie dokońca są te funkcjonalności intuicyjne. Nie ma możliwości wyboru ilu zawodników chcemy mieć na jednej stronie. Nie ma możliwości filtrowania przez dominującą nogę, osiągnięcia oraz alternatywną pozycję zawodnika.

Brak wyrażnego podziału na kolumny.


:white_square_button: *Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?*

Interfej aplikacji mi się nie podoba. Wygląda jak schemat, a nie gotowa aplikacja. Wygląd aplikacji nie jest czytelny, a zakładki są dziwnie rozmieszczone. Moim zdaniem powinny one być w poziomie, a nie w pionie. Layout jest też za szeroki, więkość aktualnych aplikacji układana jest w środkowej części.

:white_square_button: *Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).*

Nie miałam problemu ze znalezieniem formularza dodawania nowego zawodnika piłki nożnej do systemu, ale moim zdaniem znajduje się on w dziwnym miejscu. Powinien znajdować się przy zakładach, a nie tylko na stronie głównej. Ponadto powinno się to właśnie nazywać formularz, a nie linki pomocnicze.

W filtrach brakuje pół wyborów w skończonych kategoriach np. pozycje zawoników są już określone, a w tej aplikacji jest możliwość wpisywania "czegokolwiek".


:white_square_button: *Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń!* :wink:

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

:point_right:[Google exel file with Subtask 1](https://docs.google.com/spreadsheets/d/1GCCXNPcKsoPUBCMYPSMUOpLdvg_PyNnJ/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)

## **Subtask 2** 

:point_right:[Google exel file with Subtask 2](https://docs.google.com/spreadsheets/d/1AAmcIa7zSUd9py2PaPOrjbgemBezKZJ3/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)


## **Subtask 3** 

:white_square_button: *Po co piszemy test case’y?*

Warto pisać przypadki testowe, ponieważ jest to dobry sposób na spisanie wiedzy na temat testowanej aplikacji/systemu. Przypadki testowe pomagają w trakcie testowania poprawności oprogramowania, ponieważ porządkują pracę. Dzięki czemu wiadomo, ile funkcjonalności jeszcze zostało nam do przetestowania. Dobry przypadek testowy powinien odpowiadać na pytanie: __„Co tak naprawdę chcę przetestować?”__ Ponadto po zakończeniu testów, na podstawie przypadków testowych tester może tworzyć raporty z wykonanych testów na danej aplikacji/systemie.

## **Subtask 4** 

:point_right:[Google exel file with Subtask 4](https://docs.google.com/spreadsheets/d/1y0K49Haq27BUf7IkJgaE6jj7aj6kVhOM/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)

# **Task 3** 

## **Subtask 1** 

:point_right:[Subtask 1  - Bug files](https://drive.google.com/drive/folders/1JixfAMyjrwzN8rfYeg_LuM0dOhTPa_kA?usp=share_link)

## **Subtask 2** 

:point_right:[Google exel file with Subtask 2  - Bug reports](https://docs.google.com/spreadsheets/d/1uu-Nfliq6UwBACkz586v2ltJNb2WSb_q/edit?usp=share_link&ouid=103264474520704327668&rtpof=true&sd=true)


## **Subtask 3** 

:point_right:[Google exel file with Subtask 3 -Bug Tracker](https://docs.google.com/spreadsheets/d/15diIoCJH5uVvKA3STjQALmZZoe-7LPNg1GsM2xaEkdw/edit?usp=share_link)

# **Task 4** 

## **Subtask 2** 

:point_right:[Google exel file with Subtask 2  - Bug reports for olx mobile app](https://docs.google.com/spreadsheets/d/1F3OltshEVVxs_bxf95M7vX97dPAOfj84/edit#gid=418525387)

## **Subtask 3** 

:white_square_button: *Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?* 

Aplikacja olx służy do sprzedawania wystawianych lub kupowania wystawionych przedmiotów i usług. Ogłoszenia zawierają się w różnych kategoriach takich jak: Moda, Zwierzęta, Dla Dzieci, Sport i Hobby, Muzyka i Edukacja, Usługi i Firmy. 

:white_square_button: *Kto ma być użytkownikiem końcowym aplikacji?* 

Użytkownikiem końcowym są osoby wyszukujące i nabywają dany produkt/usługę.

:white_square_button: *Czy według Ciebie aplikacja jest user friendly? (Przyjazna dla użytkownika- np. wchodzisz do aplikacji i szybko łapiesz do czego służą przyciski. Poczytaj na ten temat w internecie- co to znaczy, że aplikacja jest przyjazna dla użytkownika)* 

Tak, dla mnie apliacja Olx jest user friendly :ok_hand: Olx ma dobrze zbudowaną nawigację, posiada przyciski wykonywania akcji (CTA) oraz inteligentną wyszukiwarkę. 

:white_square_button: *Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? (Żeby nie było: nie jest to aplikacja przy której pracuję, takie pytania pojawiają się na rozmowach rekrutacyjnych dlatego dobrze jest to przećwiczyć :D )* 

Mam pomysł na nową fukcjonalność. :raising_hand_woman: 	
Po wybraniu Kategorii - przycisk sprawdź Lolanie. Po czym  wyświetlanie się mapy gdzie można odebrać towar lub gdzie można nabyć usługę, ułatwiłoby to poszukiwanie usług w pobliżu. :house_with_garden:


:white_square_button: *Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?*

Testowanie funkcjonalności i wydajności aplikacji natywnych jest bardziej skomplikowane, ponieważ muszą one być testowane na różnych platformach i urządzeniach, podczas gdy aplikacje internetowe są testowane tylko na różnych przeglądarkach i konfiguracjach.
Ponad to testowanie interfejsu użytkownika aplikacji natywnych jest bardziej złożone, ponieważ interfejs użytkownika jest dostosowywany do platform (zwykle Google Play oraz App Store) , podczas gdy aplikacje internetowe mają taki sam interfejs na wszystkich urządzeniach. W przypadku aplikacji natywnej doodatkowo wymagana jest instalacja.

# **Task 5** 

## **Subtask 1** 
![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-1/Zrzut%20ekranu%202023-02-14%20161517.png)
![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-1/Zrzut%20ekranu%202023-02-14%20161541.png)
![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-1/Zrzut%20ekranu%202023-02-14%20161600.png)
![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-1/Zrzut%20ekranu%202023-02-14%20161612.png)
![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-1/Zrzut%20ekranu%202023-02-14%20161625.png)

## **Subtask 3** 
:white_square_button: **1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**

SELECT * FROM  actors ORDER BY surname

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-13%20at%2016-28-30%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20actors%20phpMyAdmin%205.2.0.png)

:white_square_button: **2. Wyświetl film, który powstał w 2019 roku.**

SELECT * FROM movies WHERE year_of_production=2019

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-13%20at%2016-33-57%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20phpMyAdmin%205.2.0.png)

:white_square_button: **3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**

SELECT * FROM movies WHERE year_of_production BETWEEN 1900 AND 1999

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-13%20at%2016-36-22%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20movies%20phpMyAdmin%205.2.0.png)

:white_square_button: **4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$**

SELECT title, price FROM movies WHERE price <7

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-13%20at%2021-54-09%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20movies%20phpMyAdmin%205.2.0.png)

:white_square_button: **5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**

SELECT * FROM actors WHERE actor_ID >=4 AND actor_ID <=7

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-13%20at%2022-01-51%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20actors%20phpMyAdmin%205.2.0.png)

:white_square_button: **6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**

SELECT * FROM `customers` WHERE customer_id=2 OR customer_id=4 OR customer_id=8

SELECT * FROM `customers` WHERE customer_id%2=0

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-14%20at%2019-05-43%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20phpMyAdmin%205.2.0.png)

:white_square_button: **7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**

SELECT * FROM `customers` WHERE customer_id IN (1,3,5)

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-14%20at%2009-24-55%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20customers%20phpMyAdmin%205.2.0.png)

:white_square_button: **8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**

SELECT * FROM `actors` WHERE name LIKE 'AN%'

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-13%20at%2022-14-00%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20actors%20phpMyAdmin%205.2.0.png)

:white_square_button: **9. Wyświetl dane klienta, który nie ma podanego adresu email.**

SELECT * FROM `customers` WHERE email IS NULL

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screens-2/Screenshot%202023-02-13%20at%2022-16-23%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20customers%20phpMyAdmin%205.2.0.png)

:white_square_button: **10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**

SELECT * FROM movies WHERE price>9 and movie_id BETWEEN 2 AND 8

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-13%20at%2022-24-49%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20movies%20phpMyAdmin%205.2.0.png)

# **Task 6** 

## **Subtask 1**

:white_square_button: **11.Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈**

UPDATE`customers` SET surname = 'Miler' WHERE name ='Ania'

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-19%20at%2019-55-23%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20customers%20phpMyAdmin%205.2.0.png)

:white_square_button: **12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.**

SELECT name, email, movie_id FROM sale AS s INNER JOIN customers AS c ON s.customer_id = c.customer_id WHERE movie_id = 4

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-19%20at%2022-09-46%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20sale%20phpMyAdmin%205.2.0.png)

:white_square_button: **13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com**

UPDATE customers SET email = 'pati@mail.com' WHERE name = 'Patrycja'

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-19%20at%2020-28-03%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20customers%20phpMyAdmin%205.2.0.png)

:white_square_button: **14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**

SELECT name, surname, title FROM sale AS s INNER JOIN customers AS c ON s.customer_id = c.customer_id INNER JOIN movies AS m ON s.movie_id = m.movie_id ORDER BY sale_date

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-19%20at%2022-26-30%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20sale%20phpMyAdmin%205.2.0.png)

:white_square_button: **15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag**

ALTER TABLE customers ADD pseudonim VARCHAR(3);
UPDATE customers SET pseudonim = CONCAT(LEFT(name, 2), RIGHT(surname, 1))

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-20%20at%2010-08-14%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20customers%20phpMyAdmin%205.2.0.png)

:white_square_button: **16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**

SELECT DISTINCT title FROM sale JOIN movies ON sale.movie_id = movies.movie_id

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-20%20at%2010-38-41%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20movies%20phpMyAdmin%205.2.0.png)

:white_square_button: **17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)**

SELECT name FROM actors 
UNION 
SELECT name FROM customers ORDER BY name ASC

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-20%20at%2010-49-54%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20sale%20phpMyAdmin%205.2.0.png)

:white_square_button: **18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).**

UPDATE movies SET price = price + 2.5 WHERE year_of_production>2000

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-20%20at%2011-31-45%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20movies%20phpMyAdmin%205.2.0.png)

:white_square_button: **19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał**

SELECT name, surname, title FROM actors JOIN cast ON actors.actor_id = cast.actor_id JOIN movies ON cast.movie_id = movies.movie_id WHERE actors.actor_id = 4

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-20%20at%2011-03-26%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20cast%20phpMyAdmin%205.2.0.png)

:white_square_button: **20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa**

INSERT INTO customers (customer_id, name, surname, email, pseudonim) VALUES (7, 'Honorata', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Screenshot%202023-02-21%20at%2009-39-59%20localhost%20_%20127.0.0.1%20_%20kurs_tester_manualny%20_%20customers%20phpMyAdmin%205.2.0.png)

## **Subtask 2**

![](https://raw.githubusercontent.com/JustynaJac/challenge_portfolio_justyna/screen-3/Zrzut%20ekranu%202023-02-20%20120826.png)

Almost ... :construction_worker:

## **Subtask 3**

:point_right: [Portfolio](https://github.com/JustynaJac/portfolio)
