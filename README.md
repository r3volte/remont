Remontowy Manager Budżetu
🚀 Wprowadzenie
Remontowy Manager Budżetu to prosta, ale potężna aplikacja internetowa stworzona do śledzenia i zarządzania wydatkami podczas remontu lub urządzania mieszkania. Projekt ewoluował z koncepcji arkusza kalkulacyjnego w pełni funkcjonalne, chmurowe narzędzie analityczne, umożliwiające współpracę w czasie rzeczywistym.

Aplikacja jest wdrożona na GitHub Pages i wykorzystuje Firebase jako backend, co zapewnia synchronizację danych między wieloma użytkownikami i urządzeniami.


✨ Kluczowe Funkcjonalności
  Analityczny Panel Główny: Interaktywny dashboard z kluczowymi wskaźnikami (budżet, wydatki, pozostała kwota) oraz wizualizacjami danych (wykres kołowy i słupkowy).

Synchronizacja w Czasie Rzeczywistym: Dzięki integracji z Firebase Firestore, wszystkie dane są natychmiast synchronizowane między wszystkimi użytkownikami.

Zarządzanie Wydatkami: Szczegółowe śledzenie kosztów z podziałem na koszt produktu i transportu.

Zarządzanie Projektem: Możliwość śledzenia statusu każdego zakupu (Na liście życzeń, Do kupienia, Zamówione, Dostarczone).

Interaktywna Lista Życzeń: Dedykowana sekcja do planowania przyszłych zakupów wraz z automatycznym podsumowaniem szacowanych kosztów.

Narzędzia Analityczne: Filtrowanie, sortowanie oraz eksport danych do formatu CSV w celu dalszej analizy (np. w Power BI).

Bezpieczeństwo: Aplikacja zabezpieczona przez Firebase App Check z integracją reCAPTCHA v3, chroniąca przed nieautoryzowanym dostępem do bazy danych.

Nowoczesny Interfejs: Przejrzysty, responsywny design z trybem ciemnym (Dark Mode).

🛠️ Tech Stack
Frontend: HTML5, Tailwind CSS, JavaScript (ES6)

Backend & Baza Danych: Google Firebase (Firestore, Authentication)

Wizualizacja Danych: Chart.js

Bezpieczeństwo: Firebase App Check, Google reCAPTCHA v3

Hosting: GitHub Pages

📜 Changelog (Historia Zmian)
v2.2 - Usprawnienia Funkcjonalne (14.09.2025)
Dodano: Osobne pole na koszt transportu w formularzu.

Dodano: Automatyczne podsumowanie szacowanej kwoty na stronie "Listy Życzeń".

Dodano: Interaktywny selektor statusu w tabelach, umożliwiający szybką zmianę stanu zadania bez wchodzenia w tryb edycji.

Aktualizacja: Logika dashboardu i wykresów uwzględnia teraz całkowity koszt (produkt + transport).

v2.1 - Wdrożenie Zabezpieczeń (14.09.2025)
Dodano: Integrację z Firebase App Check w celu zabezpieczenia backendu.

Dodano: Konfigurację reCAPTCHA v3 jako dostawcy dla App Check.

Poprawka: Rozwiązano problem alertu bezpieczeństwa "Public API Key Leak" zgłaszanego przez GitHub Secret Scanning.

Poprawka: Uzupełniono brakującą strukturę HTML, która powodowała niepoprawne renderowanie strony.

v2.0 - Migracja do Chmury (13.09.2025)
Kluczowa Zmiana: Zastąpiono localStorage bazą danych Firebase Firestore. Aplikacja stała się narzędziem do współpracy w czasie rzeczywistym.

Dodano: Funkcję anonimowego logowania użytkowników (Firebase Authentication).

Wdrożenie: Aplikacja została opublikowana w internecie za pomocą GitHub Pages.

v1.6 - Reorganizacja Interfejsu (13.09.2025)
Dodano: Interfejs oparty na zakładkach (Panel Główny, Zarządzanie Wydatkami, Lista Życzeń) dla lepszej organizacji.

Refaktoryzacja: Dostosowano kod JavaScript do obsługi nowej, wielostronicowej struktury.

v1.5 - Rozbudowa Analityczna (13.09.2025)
Dodano: Dashboard analityczny z wykresami (kołowy i słupkowy) do wizualizacji danych.

Dodano: Funkcje filtrowania po kategorii/pomieszczeniu i sortowania listy wydatków.

Dodano: Opcję eksportu danych do pliku .csv.

Dodano: Możliwość śledzenia statusu dla każdego wpisu.

Dodano: Tryb ciemny (Dark Mode) i pola na linki do produktów/zdjęć.

v1.1 - Uproszczenie Modelu Danych (12.09.2025)
Usunięto: Pole "Kto zapłacił?" w celu dostosowania do modelu wspólnego budżetu.

Dodano: Ustawiono stały, globalny budżet na poziomie 15 000 zł.

v1.0 - Pierwsza Wersja Webowa (12.09.2025)
Stworzenie: Pierwsza, w pełni funkcjonalna wersja aplikacji działająca lokalnie.

Funkcjonalność: Dodawanie, edycja i usuwanie wpisów z zapisem danych w localStorage.

UI: Prosty interfejs oparty na Tailwind CSS.

v0.1 - Koncepcja (12.09.2025)
Pomysł: Utworzenie narzędzia do śledzenia wydatków remontowych w formie arkusza kalkulacyjnego.
