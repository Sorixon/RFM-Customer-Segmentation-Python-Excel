# 📊 Analiza Segmentacji Klientów (E-commerce RFM)

Projekt skupia się na segmentacji bazy ponad 4300 klientów sklepu internetowego przy użyciu modelu RFM (Recency, Frequency, Monetary), aby zidentyfikować kluczowe grupy zakupowe i zoptymalizować strategię marketingową.

### 🛠️ Wykorzystane technologie

- **Python** (Pandas) – czyszczenie danych (500k+ wierszy), obsługa zwrotów, obliczenia statystyczne.
- **Excel** – budowa interaktywnego Dashboardu, tabele przestawne, fragmentatory (Slicers).

### 📈 Kluczowe Wnioski z Analizy RFM :

- **Potęga Mistrzów**: Segment „Mistrzów” stanowi mniejszość bazy (ok. 14%), ale generuje niemal **49% całkowitego przychodu** firmy. To kluczowa grupa dla stabilności biznesu.
- **Zasada Pareto w Praktyce**: Połączone segmenty „Mistrzów” i „Lojalnych klientów” odpowiadają za **75% obrotu**. Utrzymanie relacji z tymi grupami jest ważniejsze niż pozyskiwanie nowych użytkowników.
- **Potencjał Reaktywacji**: Grupa „Uśpieni” jest najliczniejsza (1065 osób), ale generuje tylko 6% przychodu. Sugeruje to konieczność wdrożenia niskokosztowych kampanii mailingowych w celu ich przypomnienia o marce.
- **Ryzyko Odpływu**: Ponad 580 klientów znajduje się w segmencie „Zagrożeni” (dawniej lojalni, którzy przestali kupować). Ich odzyskanie to priorytet dla działu Customer Success.

### 📂 Zawartość

- **ANALIZA_RFM.ipynb** - Pełny kod w Pythonie: czyszczenie danych, usuwanie zwrotów, scoring RFM i eksport wyników.
- **Wyniki_RFM_E-commerce.xlsx** - Gotowy, interaktywny dashboard w Excelu umożliwiający filtrowanie segmentów.
