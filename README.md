# Task 1
## *Subtask 1*
7 punktów 😀
## *Subtask 3*
Na moją decyzję, by przystąpić do QA Challenge, wpłynęła możliwość uzyskania praktycznej wiedzy oraz stworzenia portfolio.<br>
W zeszłym miesięcy stwierdziłam, że chcę coś zmienić w swojej karierze i zaczęłam działać.💪 <br>
Dlatego nie tracąc czasu, szukam możliwości zdobywania wiedzy i rozwoju.🧐 Chciałabym, żeby ten projekt, wskazał mi ścieżkę, <br>
którą powinnam podążyć, by osiągnąć swój cel i zostać testerem manualnym a w przyszłości testerem automatyzującym.☺

*<b>Iza<b/>*
  
## *Subtask 4* 
  
### *Opis aplikacji*
  
Aplikacja służy do zarządzania graczami. Analizowania każdego zawodnika,<br> 
kontroli jego udziału w meczach oraz tworzenia raportów podsumowujących.
  
### *Opis i ocena użyteczności*🧐

Logowanie/wylogowanie,<br>
Wybór języka/zmiana języka,<br>
Przejście między stroną główną a podstroną gracze,<br>
Dodawanie graczy,<br>
Przejście do podstrony Mecze, Raporty,<br>
Tworzenie raportów, generowanie pliku CSV, drukowanie raportów, <br> wyszukiwanie za pomocą filtru, zmiana wyświetlanych kolumn,<br>
Dodawanie meczy,<br>
Dodawanie raportów,<br>
Edycja raportów,<br>
Tworzenie listy zdarzeń,<br>

Zmieniłabym miejsce pojawiania się filtru w zakładce gracze (gdy jest używany, zakrywa część informacji, co może przeszkadzać użytkownikom). 
Dodałabym bezpośrednią zakładkę mecze (możliwość wyszukania gracza po danym meczu). Mało intuicyjne jest pojawianie się zakładki Mecze i Raporty dopiero po wejściu w gracza.
Dodałabym również zakładkę ostatnio przeglądani gracze. Myślę, że fajną funkcjonalnością byłoby porównywanie wybranych graczy bezpośrednio w aplikacji. 
Bardzo przydatny byłby samouczek, w zakładce MECZE. Ciężko zorientować się gdzie można wprowadzić elementy z LISTY ZDARZEŃ. 
Cała zakładka ROZPOCZNIJ MECZ, jest bardzo przytłaczająca, ze względu na brak informacji co można tam wykonać i jak to zrobić.
  
### *Ocena wizualna*👀
  
Wygląd jest w porządku, jednak mało atrakcyjny i przypominający formularze google. Interfejs jest prosty w odbiorze i czytelny.
  
### *Ocena praktyczna*🦾
  
Aplikacja nie sprawia problemów z dodawaniem i wyszukiwaniem graczy. Mało intuicyjne jest to, że dodanie gracza jest jedynie na stronie głównej, 
szukałam tej opcji w panelu gracze. Trochę nieintuicyjne jest również pojawianie się zakładki MECZE i RAPORTY dopiero po wejściu w wybranego gracza. 
Ciężko zrozumieć, o co chodzi z panelem, do którego przechodzimy po kliknięciu przycisku: ROZPOCZNIJ MECZ, w zakładce MECZE, w kolumnie AKCJE. 
Przydałby się jakiś samouczek czy instrukcja wyjaśniająca co tam się pojawia i co możemy edytować i jak to robić.
  
### *Uwagi*❗️
  
*Błędy tłumaczenia.*<br>
  
  
W zakładce GRACZE w filtrach (przy zmianie języka na polski nie wszystkie elementy są przetłumaczone: Filters, Reset, Age, Rate)
Informacja po najechaniu na ikony w prawym górnym rogu również pozostaje w języku angielskim: (download CSV, print, view columns, filter table). W formularzu dodawania nowego gracza nieprzetłumaczone (submit, clear).<br>

*Braki walidacji.*<br>
Podczas dodawania nowego gracza brak walidacji pól poza informacją, że są wymagane. Po nie poprawnym uzupełnieniu wyświetla się informacja, że nie można dodać gracza, ale nie ma informacji, które pola są niepoprawne i co jest w nich wymagane. Można wprowadzić błędną datę urodzenia, nawet z przyszłości.

*Brakujące funkcjonalności.*<br>
Brak możliwości usunięcia gracza. Brak możliwości usunięcia raportu. Brak możliwość dodania gracza w zakładce gracze.

*Trudności w użytkowaniu.*<br>
W zakładce MECZE po wejściu w AKCJĘ > ROZPOCZNIJ MECZ, wyświetla się plansza, w której nie działa ikona usuń. Reszta przycisków jest mało intuicyjna, można by dodać informację, co wydarzy się po kliknięciu, np. w dymku po najechaniu na daną ikonę. Informacja o wysłaniu raportu jest mało pomocna, gdyż nie wiemy jaki raport i gdzie właściwie został wysłany. Po dodaniu komentarza nie można go podejrzeć, nigdzie się nie wyświetla. Brak możliwości edycji kropek na planszy, komentarzy.<br>

*Inne.*<br>
Wygenerowany plik CSV nie zawiera wszystkich informacji, za każdym razem generuje te same dane niezależnie od ustawień widoczności kolumny.
W raporcie meczowym brak ograniczeń w ilości znaków w komentarzach oraz opisach w samym raporcie. 
  
 # Task 2
## *Subtask 1*
[Pisanie przypadków testowych na podstawie User Story](https://docs.google.com/spreadsheets/d/13f2iqdep8BKwsPF7rjy1svQQyzAo3J7GURKwKrdvizE/edit?usp=sharing)

## *Subtask 2*
 [Pisanie przypadków testowych na podstawie własnych doświadczeń](https://docs.google.com/spreadsheets/d/16COdGQQfwThK76CaQQtvQNyTWjrp5gBTCHjcr5HlxRs/edit?usp=sharing)
  
  ## *Subtask 3*
  
  ### *Po co piszemy przypadki testowe?*
  
  Przypadki testowe piszemy w celu udokumentowania możliwości modułów w danej aplikacji. Dobrze napisane przypadki pozwalają nam na pokrycie wszystkich funkcjonalności oprogramowania, pomagają w stworzeniu raportu z testów. Przypadki testowe będą przydatne dla osób, które dopiero poznają daną aplikację. Mogą również odegrać ważną rolę podczas testów akceptacyjnych, potwierdzając działanie aplikacji w oczekiwany sposób.

*Skracając, przypadki testowe pozwalają nam na posortowanie, przetestowanie i skontrolowanie tego, co i w jaki sposób można wykonać w danej aplikacji.*
  
  
  [![Komu to potrzebne? A dlaczego?](https://fabrykamemow.pl/uimages/services/fabrykamemow/i18n/pl_PL/201708/1502827036_by_anonymous_500.jpg?1502827036)](https://www.youtube.com/embed/OO3FANjwKHY?start=1)
  
   ## *Subtask 4*
  [Pisanie przypadków testowych na podstawie własnych doświadczeń](https://docs.google.com/document/d/164lum8wfixR88mhimARGnkl_FtmL5E5n7eGDKlgOF60/edit?usp=sharing)
  
 *Aplikacja Pick Eat Up -> https://pickeatup.io/*
  
  
  
  # Task 3
## *Subtask 1*
  [BUG REPORT](https://docs.google.com/document/d/1sO9JV0Qvad12yiDPhfAgDWd7PhxmwAdM-mNU8G-1tuw/edit?usp=sharing)🕵️‍♀️
  
## *Subtask 2*
  [PRODUCTION TESTING part1](https://docs.google.com/spreadsheets/d/13f2iqdep8BKwsPF7rjy1svQQyzAo3J7GURKwKrdvizE/edit?usp=sharing) <br>
  
[PRODUCTION TESTING part2](https://docs.google.com/spreadsheets/d/16COdGQQfwThK76CaQQtvQNyTWjrp5gBTCHjcr5HlxRs/edit?usp=sharing)
  
## *Subtask 3*
  [REPORT](https://docs.google.com/document/d/1hk10oz3M5G8V2kedF53JsuEHQGy_1ZaIR7jWWBwVqRk/edit?usp=sharing) 
 
## *Subtask 4*
 
  [EXPLORATORY TESTING SESSION](https://docs.google.com/document/d/1CknR6nF_Zg4zOYx8hCHcSHg6sTVAcTab7LOf6vR-vMs/edit?usp=sharing)
  
 # Task 4
## *Subtask 2*
[BUG REPORT Focusly](https://docs.google.com/spreadsheets/d/1_b4XZgE24yGXYqKL3lu7vxpsy__a_yBAma0oS6CHfto/edit?usp=sharing)🕵️‍♀️
## *Subtask 3*

  *1* <br>
Aplikacja służy do medytacji oraz
pracy nad sobą i swoimi emocjami. 🌸 Celem aplikacji jest promowanie
medytacji oraz technik relaksacyjnych i rozwojowych z nią związanych.
  
*2*<br>
  Użytkownikiem końcowym aplikacji mają być dorośli oraz dzieci
w wieku szkolnym i starsze.👨‍👩‍👧‍👦
  
  *3*<br>
Moim zdaniem aplikacja na początku za bardzo przytłacza użytkownika ilością
okien, pomiędzy którymi można przechodzić z poziomu
menu głównego. Kolorystyka jest przyjazna, przyciski w większości są intuicyjne.👌
  
  *4*<br>
  Wprowadziłabym rozbudowany samouczek, który by pozwolił na zrozumienie
podziału i funkcji aplikacji. Dodałabym również informacje (ikonka serduszka❤️) przy
nagraniach, które zostały dodane do listy ulubionych. Przydatna by była również
informacja przy nagraniach, które już zostały w całości przesłuchane👂, a które są do dokończenia.

*5*<br>
Testowanie aplikacji internetowej jest zdecydowanie wygodniejsze ze względu
na rozdzielczość ekranu i poruszanie się w środowisku komputerowym.💻  Aplikacja natywna nie zawsze
pozwala nam na szybkie zidentyfikowanie anomalii ze względu na możliwość chybienia przez nas w przycisk
lub wady urządzenia, na którym jest dana aplikacja testowana.👩🏼‍💻 
  
  ## *Subtask 4*
[BUG REPORT swipeto.pl](https://testerzy.atlassian.net/)🕵️‍

# Task 5
## *Subtask 1*
  
SELECT
FROM
DESC 
WHERE
BETWEEN
LIKE
NULL
IS
AND
OR
  
## *Subtask 3*  
  
1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
  
SELECT * FROM actors ORDER BY surname<br>
![1](https://user-images.githubusercontent.com/113973677/204655283-6dca669b-f702-438a-96ca-495b6abf76e6.png)<br>

 
2. Wyświetl film, który powstał w 2019 roku.
  
SELECT * FROM movies WHERE year_of_production = 2019 <br><br>
![2](https://user-images.githubusercontent.com/113973677/204655323-14b6e9ae-2f07-4004-b729-1508f36c0860.png)<br>


3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
  
SELECT * FROM movies WHERE year_of_production BETWEEN 1900 AND 1999 <br>
![3](https://user-images.githubusercontent.com/113973677/204655476-4488d093-8c43-408d-a181-78f47d3e8aa5.png)<br>


4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 
  
SELECT * FROM movies WHERE price <= 7 <br>
![4](https://user-images.githubusercontent.com/113973677/204655520-2ad710b9-98a0-40e1-8200-2141d9e360b8.png)<br>


5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
                                       
SELECT * FROM actors WHERE actor_id >= 4 AND actor_id <=7 <br>
![5](https://user-images.githubusercontent.com/113973677/204655555-d32d0772-6a4e-4331-8bb3-b28164af38fa.png)<br>


6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 
                                                             
SELECT * FROM customers WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6<br>
![6](https://user-images.githubusercontent.com/113973677/204655610-010f64bd-445d-4762-bd12-5825ca2806ed.png)<br>


7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN. 
                                                             
SELECT * FROM customers WHERE customer_id IN (1, 3, 5) <br>
![7](https://user-images.githubusercontent.com/113973677/204655629-25973444-7278-4ae9-996c-337baf4f9ad7.png)<br>

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
                                                             
SELECT * FROM actors WHERE name LIKE 'An%'<br>
![8](https://user-images.githubusercontent.com/113973677/204655666-c2d2dfc3-821c-41ab-afe9-f62b6a4a9f42.png)<br>
 

9. Wyświetl dane klienta, który nie ma podanego adresu email.
                                                             
SELECT * FROM customers WHERE email IS NULL<br>
![9](https://user-images.githubusercontent.com/113973677/204655691-2dcd8083-ad2b-4901-bfaf-9d21c1807d07.png)<br>
           

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
                                                             
SELECT * FROM movies WHERE price>9 AND movie_id BETWEEN 2 AND 8<br>
![10](https://user-images.githubusercontent.com/113973677/204655709-cfcc8170-ae79-4153-a0cf-bf17d00d3c8b.png)<br>
  
# Task 6
## *Subtask 1*  
11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈 
UPDATE customers
SET surname = 'Miler'
WHERE customer_id=3  
  
  
17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie.   
SELECT name FROM actors 
UNION
SELECT name FROM customers
ORDER BY name
