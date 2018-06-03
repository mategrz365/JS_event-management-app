# JS_event-management-app

Funkcjonalność i elementy:
1) Tworzenie nowego wydarzenia. Wymagane informacje:
    - tytuł wydarzenia,
    - opis wydarzenia,
    - nazwa organizatora,
    - lokalizacja,
    - data, początek - koniec (date picker),
    - zdjęcie wydarzenia (wystarczy link do obrazka, który jest hostowany na zewnątrz),
    - kategoria (do wyboru jedna z 5 dowolnych kategorii),
2) Wyświetlanie wszystkich utworzonych wydarzeń
3) Możliwość wyszukiwania po tytule i/lub lokalizacji, filtrowanie lub sortowanie
4) Usuwanie wydarzenia
5) Edycja wydarzenia
6) Zapisywanie stanu aplikacji w IndexedDB z przywróceniem stanu po otwarciu/odświeżeniu aplikacji 
7) GUI 
8) README potrzebne informacje do uruchomienia projektu.

Możliwość rozbudowy:
- Testy
- Google API do lokalizacji (autocomplete, mapy, etc.)
- File API do wczytywania zdjęcia i hostowanie przy użyciu darmowego API (przykład https://api.imgur.com/)
- Ładne, przejrzyste UI oraz animacje
- Licznik dni pozostałych do rozpoczęcia wydarzenia
- Użycie Firebase lub innego rozwiązania do persystencji danych (oprócz local storage).
- Pobieranie lokalizacji użytkownika i obliczanie odległości od danego wydarzenia
- Ostrzeżenie przy usuwaniu czy jesteśmy tego pewni

Przykład: eventbrite.com
