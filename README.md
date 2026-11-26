# metadetlaf

Aplikacja do tworzenia listy zakupów.
Pole tekstowe, pole ilości i przycisk „Dodaj”. Dodawanie działa też po naciśnięciu Enter (formularz +
submit ).
Walidacja: nazwa nie może być pusta ani składać się z samych spacji ( trim() ), ilość musi być liczbą
większą od 0. Błędy wyświetlane na czerwono pod formularzem.
Nowa pozycja dodawana do listy w formacie „Mleko – 2 szt.” wraz z przyciskiem „Usuń”.
Kliknięcie nazwy produktu oznacza go jako kupiony ( toggleClass : przekreślenie, szary kolor) i
ponowne kliknięcie cofa oznaczenie.
Licznik: „Do kupienia: 4, kupione: 2”, aktualizowany po każdej zmianie.
Przycisk „Usuń kupione” usuwa wszystkie oznaczone pozycje.
Gdy lista jest pusta, wyświetla się komunikat „Lista jest pusta”.
Minimalna liczba commitów: 8 (start projektu + 7 wymagań)
