# Wytyczne stylu pisania - raport naukowo-techniczny

## 1. Ogólna charakterystyka stylu

Tekst reprezentuje styl polskiego raportu naukowo-technicznego o charakterze sprawozdawczym (raport roczny z realizacji zadania badawczego). Jest to styl formalny, rzeczowy, silnie osadzony w terminologii dziedzinowej (elektromagnetyzm, metoda elementów skończonych, nauka o materiałach). Autor pisze w sposób chronologiczny, relacjonując kolejne etapy prac badawczych, ich wyniki i wnioski.

## 2. Struktura narracyjna

### 2.1. Schemat relacjonowania prac

Autor konsekwentnie stosuje powtarzalny schemat opisu każdego etapu badań:

1. Wskazanie podzadania lub kontekstu ("W ramach podzadania 3.1...")
2. Opis podjętych działań ("opracowano...", "przeprowadzono...")
3. Prezentacja wyników z odwołaniem do rysunków i tabel
4. Sformułowanie wniosków ("Stwierdzono, że...")
5. Decyzja o dalszym kierunku prac ("Wobec tego zdecydowano...")

### 2.2. Logika decyzyjna

Charakterystycznym elementem stylu jest jawne dokumentowanie decyzji metodologicznych, w tym decyzji o rezygnacji z danego podejścia. Autor prezentuje próbowane rozwiązania, wyjaśnia przyczyny ich odrzucenia i uzasadnia wybór alternatywnego podejścia. Schemat ten powtarza się wielokrotnie:

- próba zastosowania solvera MUMPS --> rezygnacja z powodu braku konwergencji i nadmiernych wymagań pamięciowych
- próba zastosowania pełnego modelu anizotropowego --> rezygnacja z powodu kosztu obliczeniowego (z zastrzeżeniem wykorzystania do walidacji)
- próba zastosowania modelu "Laminate Stack Model" --> rezygnacja z powodu nieadekwatności fizycznej wobec stochastycznego charakteru zjawisk w rdzeniach FINEMET
- próba zastosowania oryginalnego modelu Steinmetza dla rdzenia ze szczeliną --> stwierdzenie niewystarczalności i opracowanie wielomianowego rozszerzenia modelu

## 3. Składnia i konstrukcje zdaniowe

### 3.1. Strona bierna i formy bezosobowe

Dominująca cecha składniowa to konsekwentne stosowanie strony biernej i form bezosobowych. Autor unika pierwszej osoby (zarówno liczby pojedynczej, jak i mnogiej). Typowe konstrukcje:

- "skupiono się na realizacji..."
- "opracowano trójwymiarowy model..."
- "przeprowadzono analizy..."
- "stwierdzono, że..."
- "zdecydowano, że..."
- "odstąpiono od wykorzystania..."
- "zrezygnowano z zastosowania..."

### 3.2. Zdania złożone i wielokrotnie złożone

Autor preferuje dłuższe zdania złożone, często z wieloma zdaniami podrzędnymi. Konstrukcje wieloklauzulowe są typowe, szczególnie w opisach technicznych i uzasadnieniach decyzji. Zdania są informacyjnie gęste - w jednym zdaniu łączy się opis obiektu, jego właściwości i kontekst zastosowania.

Przykład typowej długości i złożoności zdania:
> "Ze względu na wysoką, przewidywaną przenikalność magnetyczną modelowanego rdzenia przyjęto układ magnesowania za pomocą pojedynczego, ulokowanego osiowo, cylindrycznego przewodnika, który będzie zasilany prądem magnesującym."

### 3.3. Zdania wyliczeniowe

Gdy autor formułuje wnioski lub wylicza ustalenia, stosuje format listy z myślnikami lub literami (a, b, c, d). Każdy punkt wyliczenia stanowi pełne zdanie lub rozbudowany fragment zdaniowy.

## 4. Słownictwo i terminologia

### 4.1. Terminologia specjalistyczna

Autor stosuje polską terminologię techniczną, uzupełniając ją przy pierwszym użyciu oryginalnym terminem angielskim w nawiasie, oznaczonym skrótem "ang.":

- "wstępnego kondycjonowania macierzy (ang. Incomplete LU factorization -- ILU)"

Przy kolejnych użyciach stosuje już tylko termin polski lub skrót.

### 4.2. Nazwy oprogramowania i metod

Nazwy oprogramowania (ELMER FEM, NETGEN, MUMPS) i metod (BiCGStabl, Conjugate Gradient) są zapisywane w oryginalnej formie angielskiej, bez tłumaczenia i bez odmiany. Nazwy modeli są podawane w języku angielskim w cudzysłowie ("Laminate Stack Model").

### 4.3. Zwroty łączące

Autor często stosuje następujące zwroty jako elementy spajające narrację:

- "W ramach podzadania..."
- "W wyniku analizy stwierdzono, że..."
- "Z tego względu..."
- "Wobec tego..." / "Wobec powyższego..."
- "Równocześnie..."
- "W toku dalszych prac..."
- "W kolejnym etapie prac..."
- "Ponadto..."
- "Jednak..."
- "Natomiast..."

### 4.4. Wielowyrazowe określenia rzeczownikowe

Charakterystyczna cecha stylu to rozbudowane frazy nominalne (łańcuchy dopełniaczy i przymiotników), typowe dla polskiego języka naukowego:

- "trójwymiarowy model układu magnesowanego rdzenia ze szczeliną o regulowanej szerokości"
- "zastępczej wartości przewodności w rdzeniu w funkcji częstotliwości"
- "wielomianowe rozszerzenie modelu Steinmetza umożliwiające uogólniony opis zmian"

## 5. Odwołania do materiałów graficznych

### 5.1. Format odwołań

Autor stosuje konsekwentny format odwołań do rysunków i tabel:

- "Przykładowy model 3D układu podano na rysunku 1a, zaś kod skryptu (...) podano na rysunku 1b."
- "Wyniki pomiarów i modelowania zebrano w tabeli 1 oraz przedstawiono na rysunku 2."
- "Na rysunku 6a przedstawiono wyniki modelowania..."
- "Natomiast na rysunku 6b przedstawiono..."

### 5.2. Podpisy rysunków i tabel

Podpisy rysunków zaczynają się od "Rys." z numerem, po czym następuje rozbudowany opis treści. Przy rysunkach wieloczęściowych stosowane są oznaczenia a), b) z opisem każdej części po dwukropku lub myślniku.

Podpisy tabel zaczynają się od "Tabela" lub "Tab." z numerem i pełnym opisem zawartości.

## 6. Prezentacja wyników i wniosków

### 6.1. Wnioski cząstkowe

Wnioski z poszczególnych etapów są poprzedzane formułą:

- "W wyniku przeprowadzonych testów wstępnych stwierdzono, że:"
- "W wyniku zrealizowanego modelowania oraz analizy wyników (...) stwierdzono, że:"

Po formule następuje lista oznaczona myślnikami lub literami.

### 6.2. Wnioski decyzyjne

Kluczowe decyzje o zmianie kierunku badań są wyraźnie zaznaczone, niekiedy wyróżnieniem (pogrubienie tekstu). Stosowany jest schemat: konstatacja problemu --> decyzja --> uzasadnienie.

### 6.3. Wnioski podsumowujące

Podsumowanie etapu zaczyna się od słowa "Wniosek" i podaje w zwięzłej formie najważniejszy osiągnięty rezultat.

## 7. Opis planów dalszych prac

Plany są prezentowane w formie listy numerowanej, w której każdy punkt stanowi krótki opis planowanego działania. Stosowana jest forma bezosobowa ("planowane jest") lub rzeczownikowa ("opracowanie", "identyfikacja").

## 8. Cytowanie literatury i źródeł

Cytaty literaturowe są umieszczane w tekście w formie pełnego opisu bibliograficznego (nazwiska autorów, tytuł, czasopismo, tom, strony, rok, DOI) bezpośrednio w zdaniu, bez stosowania oddzielnej sekcji bibliograficznej. Adresy URL repozytoriów i konferencji są podawane bezpośrednio w tekście.

## 9. Formatowanie i konwencje typograficzne

### 9.1. Symbole i jednostki

- Symbole fizyczne są zapisywane kursywą (np. *P*, *B*, *f*, *S*)
- Jednostki są zapisywane pismem prostym z użyciem standardowych skrótów (W/m3, Hz, A/m, T)
- Indeksy dolne i górne są stosowane przy oznaczeniach (B_max, R^2, f^b)

### 9.2. Wzory matematyczne

Wzory są numerowane w nawiasach okrągłych, np. (1), i osadzane w tekście z objaśnieniem znaczenia poszczególnych symboli.

### 9.3. Kody źródłowe

Fragmenty kodów źródłowych (konfiguracje solverów, skrypty geometrii) są prezentowane w osobnych blokach opisanych jako "Kod 1", "Kod 2" itp., z podpisem wyjaśniającym przeznaczenie kodu.

## 10. Cechy rytmu i tempa narracji

Tekst ma równomierne tempo. Autor nie stosuje skrótów myślowych ani eliptycznych konstrukcji. Każdy etap jest opisany z pełnym kontekstem, nawet jeśli powoduje to powtórzenia (np. opis układu magnesowania powtarza się przy rdzeniu bez szczeliny i ze szczeliną w niemal identycznej formie). Powtórzenia te służą przejrzystości i samowystarczalności poszczególnych fragmentów raportu.

## 11. Podsumowanie kluczowych cech do odtworzenia

| Cecha | Opis |
|---|---|
| Osoba gramatyczna | Formy bezosobowe, strona bierna |
| Czas gramatyczny | Czas przeszły dokonany (stwierdzono, opracowano, zrealizowano) |
| Długość zdań | Średnia do długiej, zdania złożone podrzędnie |
| Ton | Formalny, rzeczowy, bezemocjonalny |
| Struktura | Chronologiczna, etapowa, z jawnym dokumentowaniem decyzji |
| Terminologia | Polska z angielskimi odpowiednikami przy pierwszym użyciu |
| Odwołania graficzne | Konsekwentne, w tekście, z numeracją i literami części |
| Wnioski | Poprzedzone formułą wprowadzającą, w formie list |
| Spójniki narracyjne | "Wobec tego", "Z tego względu", "Równocześnie", "W toku dalszych prac" |
| Wielowyrazowe frazy nominalne | Rozbudowane łańcuchy dopełniaczy i określników |
