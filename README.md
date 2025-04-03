# Testy Eksploracyjne – AcademyBugs

Projekt zawiera listę defektów znalezionych podczas testów eksploracyjnych strony [academybugs.com](https://academybugs.com).  
Pełna dokumentacja zgłoszeń znajduje się w pliku `.docx`. Poniżej zaprezentowano dwa przykładowe błędy.

---

## 📌 Przykładowe zgłoszenia błędów

### 🔴 Błąd 1 – Zmiana waluty powoduje crash strony

- **Priorytet**: Wysoki  
- **Opis**: Podczas zmiany waluty w zakładce „Select a Currency” strona przestaje działać.  
- **Kroki do reprodukcji**:
  1. Przejdź na stronę academybugs.com
  2. Kliknij „Find Bugs”
  3. Przejdź do zakładki „My Cart”
  4. W sekcji „Select a Currency” zmień walutę np. z USD na EUR
- **Rzeczywisty rezultat**: Strona się crashuje  
- **Oczekiwany rezultat**: Strona powinna przeliczyć wartości i działać poprawnie  
- **Dowód (film)**:
-
- [Zobacz nagranie](https://drive.google.com/file/d/1mhpAPnQyQvJhHi7R--1I2VZgx6VNyu_q/view?usp=sharing)

---

### 🔴 Błąd 2 – Brak możliwości zamówienia więcej niż 2 sztuk produktu

- **Priorytet**: Wysoki  
- **Opis**: Po zwiększeniu liczby produktu w koszyku do więcej niż 2 i kliknięciu „Update”, system automatycznie zmienia wartość z powrotem na 2.  
- **Kroki do reprodukcji**:
  1. Przejdź na stronę academybugs.com
  2. Kliknij „Find Bugs” → wybierz produkt i dodaj do koszyka
  3. Przejdź do koszyka
  4. Ustaw ilość na np. „4” i kliknij „Update”
- **Rzeczywisty rezultat**: Liczba sztuk zmienia się z 4 na 2  
- **Oczekiwany rezultat**: System powinien pozwalać na zakup większej liczby produktów, jeśli są dostępne  
- **Dowód (film)**: [Zobacz nagranie](https://drive.google.com/file/d/1P42UCoX3EUHwZnIY1X5R5USxFw2bpvMr/view?usp=sharing)



---

## 🧪 Zakres testów eksploracyjnych

- Filtrowanie produktów
- Funkcje koszyka i checkoutu
- Responsywność przycisków i elementów interfejsu
- Walidacja języka, waluty, ikon i linków
- Poprawność elementów graficznych i wyrównań

---

## 🖥️ Środowisko testowe

- System operacyjny: Windows 11 Pro 64bit  
- Przeglądarka: Opera

---

## 📎 Zawartość repozytorium

- `README.md` – opis projektu i przykłady zgłoszeń
-  📄 Plan testów – [Plan-Testów.md](./Plan-Testów.md)
- 📄 Raport z testów – [Testy Eksploracyjne - academybugs.docx](./Testy%20Eksploracyjne%20-%20academybugs.docx)

---

## 📍 Status projektu

Projekt demonstracyjny – część portfolio testera manualnego.  
Zadanie wykonane samodzielnie w ramach ćwiczeń testerskich.

