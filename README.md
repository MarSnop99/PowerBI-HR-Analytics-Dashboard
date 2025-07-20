# Dashboard Analizy Danych HR w Power BI

Ten projekt prezentuje kompleksowy dashboard analityczny zbudowany w Power BI, służący do analizy kluczowych wskaźników zasobów ludzkich.

## Podgląd Dashboardu
*Ponieważ raport zawiera dane wrażliwe, interaktywna wersja online nie jest publicznie dostępna. Poniżej znajduje się zrzut ekranu finalnego produktu.*

![Podgląd Dashboardu HR] (https://github.com/MarSnop99/PowerBI-HR-Analytics-Dashboard/blob/main/HR-PowerBI-Dashboard-Screenshot.png?raw=true)

## 1. Cel Biznesowy Projektu
Celem projektu było stworzenie interaktywnego narzędzia dla działu HR, które pozwala na szybką ocenę struktury zatrudnienia, analizę wynagrodzeń oraz identyfikację trendów demograficznych w firmie.

## 2. Użyte Technologie
*   **Power BI Desktop**
*   **Power Query:** do procesów ETL (czyszczenie, transformacja i walidacja danych z surowego pliku).
*   **DAX (Data Analysis Expressions):** do stworzenia niestandardowych miar biznesowych (m.in. Liczba Pracowników, Średnie Wynagrodzenie).
*   **Modelowanie Danych:** Stworzenie logicznego modelu w celu zapewnienia spójności i wydajności analiz.

## 3. Kluczowe Wnioski i Rekomendacje

### Wnioski z Analizy:
*   **Brak silnej korelacji między stażem pracy a wynagrodzeniem,** co sugeruje, że kluczowe są inne czynniki, takie jak dział czy stanowisko.
*   **Wysoka stabilność zatrudnienia** (średni staż >8 lat), co może wskazywać na niską rotację.
*   **Zidentyfikowano lukę płacową (pay gap)** między płciami na wielu stanowiskach oraz znaczące różnice w średnich zarobkach między działami.

### Rekomendacje Biznesowe:
1.  **Benchmarking Wynagrodzeń:** Zaleca się przeprowadzenie analizy porównawczej płac dla działów IT i Produkcji do stawek rynkowych, aby zapewnić konkurencyjność i utrzymać talenty.
2.  **Audyt Równości Płac:** Rekomenduje się przeprowadzenie dogłębnego audytu w celu zidentyfikowania przyczyn systemowych luki płacowej.
3.  **Analiza Ryzyka Demograficznego:** W związku z wysokim średnim wiekiem pracowników (ok. 41 lat), rekomenduje się wdrożenie programów planowania sukcesji.

## 4. Struktura Projektu
*   **`PowerBI-HR-Analitycs-Dashboard.pbix` ** Plik źródłowy projektu Power BI zawierający dane, model, zapytania Power Query i wizualizacje.
*   **`HR-PowerBI-Dashboard-Screenshot.png` ** Zrzut ekranu finalnego dashboardu.
