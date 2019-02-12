# Web Store
API sklepu internetowego, który obsługuje: produkty, ceny (ceny mogą się zmieniać w czasie), koszyk (listę produktów z cenami oraz ilością)

## Dostępne funkcje:

* Pobierania listy produktów
* Przeszukiwanie listy produktów po nazwie produktu
* Pobieranie danych produktu podając jego ID
* Tworzenie koszyka
* Dodawanie/Usuwanie produktów do koszyka
* Zmiana ilości produktów w koszyku
* Pobierania zawartości koszyka.

## Do zrobienia:

* ~~Zaimplementowany model bazy danych w którejś z wbudowanych baz danych (h2, hsql lub inna)~~ Zamiast bazy danych prosze o przechowywanie danych w tablicach lub mapach w obiektach typu "Repository". 
* Wprowadzone dane kilku produktów
* REST API z przykładami użycia w testach jednostkowych
    * Testy np. w pyspark 
    * Serwer moze byc ba Flask'u

* ~~Aplikacja powinna się uruchamiać z Mavena (można użyć Spring boot lub embedded Jetty/Tomcat)~~
