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
- **Dowód (film)**: [Zobacz nagranie](https://drive.google.com/file/d/1mhpAPnQyQvJhHi7R--1I2VZgx6VNyu_q/view?usp=sharing)

---

### 🟠 Błąd 2 – Błędna suma w sekcji „Cart Total”

- **Priorytet**: Wysoki  
- **Opis**: Suma końcowa w koszyku nie odpowiada sumie produktów + koszt wysyłki.  
- **Kroki do reprodukcji**:
  1. Przejdź do academybugs.com → „My Cart”
  2. Porównaj wartości w „Cart Subtotal”, „Shipping” i „Grand Total”
- **Rzeczywisty rezultat**: Grand Total pokazuje $152.99 mimo że suma powinna wynosić $52.99  
- **Oczekiwany rezultat**: Grand Total = Subtotal + Shipping  
- **Dowód (Zdjęcię)**:![image](https://github.com/user-attachments/assets/9b21cd31-014c-4c4f-8cba-373965cf25f5)


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

- `Testy Eksploracyjne - academybugs.docx` – pełna dokumentacja błędów
- `README.md` – opis projektu i przykłady zgłoszeń

---

## 📍 Status projektu

Projekt demonstracyjny – część portfolio testera manualnego.  
Zadanie wykonane samodzielnie w ramach ćwiczeń testerskich.

