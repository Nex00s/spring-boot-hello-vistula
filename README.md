# spring-boot-hello-vistula


Opis aplikacji:
Aplikacja Spring Boot działa jako prosty serwer HTTP, który wyświetla komunikat powitalny na stronie.

Funkcjonalności:
Strona powitalna ("/greeting")
Strona przyjmuje parametr o nazwie `Vistula`, który jest wyświetlany w powitaniu. Jeśli parametr nie zostanie przekazany, domyślną wartością jest "Vistula".

Przykład działania:
- Jeśli użytkownik wejdzie na stronę `http://localhost:8080/greeting?Vistula=Krystian`, zobaczy komunikat "Hello, Krystian!".
- Jeśli użytkownik wejdzie na stronę `http://localhost:8080/greeting` bez parametru, zobaczy "Hello, Vistula!".
