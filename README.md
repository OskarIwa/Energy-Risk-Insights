# 📊 Analiza Ryzyka Ekonomicznego: PKN Orlen vs Unimot (2012–2024)

## 📌 Cel projektu
Celem projektu było przeprowadzenie wielowymiarowej analizy porównawczej kondycji finansowej dwóch gigantów polskiego sektora paliwowo-energetycznego. Analiza obejmuje okres 12 lat, co pozwoliło na zbadanie stabilności spółek w obliczu skrajnych warunków rynkowych (pandemia, wojna na Ukrainie, fuzje i przejęcia).

## 🧠 Metodologia i "Logika Biznesowa"
To nie jest zwykłe zestawienie tabelaryczne. Projekt wykorzystuje **podejście algorytmiczne** do oceny ryzyka:
1. **Analiza Wskaźnikowa:** Wykorzystaliśmy 10 kluczowych wskaźników obejmujących płynność, rentowność (np.: ROA, ROE) oraz sprawność operacyjną.
2. **Modele Decyzyjne:** Zaimplementowaliśmy reguły logiczne (widoczne w pliku `decisionrules.xlsx`), które automatycznie klasyfikują stan spółki jako "Ryzyko bankructwa" (0) lub "Brak ryzyka" (1). Na zdjęciu odpowiednio wyniki reguł dla PKN Orlen i Unimot:
<img width="604" height="188" alt="Zrzut ekranu 2026-03-04 164138" src="https://github.com/user-attachments/assets/3d6d1cf1-33b2-43e0-8b9d-4e7dd0b69be0" />
<img width="603" height="187" alt="Zrzut ekranu 2026-03-04 164146" src="https://github.com/user-attachments/assets/d4212e54-e848-4d00-b00b-8ec9a92f0a8f" />

## 📈 Kluczowe wnioski z analizy (2012–2024)
Na podstawie przetworzonych danych w Excelu sformułowaliśmy następujące wnioski:

* **PKN Orlen (Skala i Fuzje):** Analiza strukturalna wykazuje gigantyczny skok wartości aktywów w 2022 roku (ponad 300% wzrostu w ujęciu łańcuchowym), co bezpośrednio odzwierciedla procesy konsolidacyjne w polskim sektorze energetycznym. Spółka wykazuje wysoką odporność na ryzyko w długim terminie dzięki ogromnej bazie kapitałowej. Na zdjęciu struktura aktywów PKN Orlen w badanym okresie.
<img width="601" height="311" alt="Zrzut ekranu 2026-03-04 163914" src="https://github.com/user-attachments/assets/9967dbc8-97b1-49a8-81dc-bffd5e81d13f" />

* **Unimot (Dynamika i Adaptacja):** Spółka mniejsza, ale o znacznie wyższej dynamice wzrostu aktywów obrotowych. Model decyzyjny wskazuje na okresowe wzrosty ryzyka płynności w latach kryzysowych, które były jednak skutecznie mitygowane przez agresywne zarządzanie kapitałem pracującym. Na zdjęciu struktura aktywów Unimot w badanym okresie.
<img width="599" height="272" alt="Zrzut ekranu 2026-03-04 164039" src="https://github.com/user-attachments/assets/1071fa8a-bde0-48a8-b417-3e7af6af9d8d" />

* **Wpływ otoczenia:** Oba podmioty wykazały zdolność do generowania rekordowych zysków netto w warunkach wysokiej zmienności cen ropy (2022/2023), co potwierdza ich strategiczne znaczenie dla bezpieczeństwa energetycznego.

## 📁 Zawartość repozytorium
* `Dane i obliczenia.xlsx` – Silnik analityczny: bilans, rachunek zysków i strat, wskaźniki KPI.
* `decisionrules.xlsx` – Implementacja modeli dyskryminacyjnych i reguł logicznych.
* `Raport-analiza ryzyka.pdf` – Dokumentacja końcowa z pełną interpretacją ekonomiczną.

*Projekt zrealizowany w ramach przedmiotu Analiza Ryzyka Ekonomicznego na Wydziale Zarządzania i Ekonomii Politechniki Gdańskiej (2026).*
