# Information Architecture

**Wersja:** 1.0  
**Status:** Draft  
**Data:** 2026-08-04  
**Właściciel:** Product

---

# Cel dokumentu

Information Architecture definiuje strukturę całego ekosystemu Pani Migrena.

Jej zadaniem jest odpowiedzieć na pytanie:

> Gdzie użytkownik powinien trafić i jaką drogę przejść, aby odzyskać poczucie sprawczości?

Dokument nie opisuje wyglądu strony ani technologii. Opisuje sposób organizacji wiedzy, narzędzi i doświadczeń użytkownika.

---

# Główna zasada

Projektujemy nie portal.

Projektujemy drogę użytkownika.

Każda strona musi odpowiadać na jedno z pytań:

- Gdzie jestem?
- Czy to miejsce jest dla mnie?
- Co mogę tutaj zrobić?
- Co powinienem zrobić dalej?

Jeżeli strona nie odpowiada na żadne z tych pytań — prawdopodobnie nie jest potrzebna.

---

# Architektura portalu

Pani Migrena

├── Strona główna
├── Wiedza
├── Migrenownik
├── Neurolodzy
├── O projekcie
├── Newsletter
└── Kontakt

---

# 1. Strona główna

Cel

Pierwszy kontakt z marką.

Po 30 sekundach użytkownik powinien pomyśleć:

• Ktoś mnie rozumie.
• To miejsce jest wiarygodne.
• Wiem, co zrobić dalej.

Najważniejsze akcje

- rozpoczęcie korzystania z Migrenownika
- przejście do wiedzy
- poznanie projektu

---

# 2. Wiedza

Cel

Dostarczenie rzetelnej wiedzy pomagającej lepiej rozumieć migrenę.

Kategorie (wersja MVP)

- Czym jest migrena
- Objawy
- Leczenie
- Leki
- Styl życia
- Przygotowanie do wizyty
- Migrenownik

Każdy artykuł powinien kończyć się kolejnym krokiem.

Nigdy "koniec artykułu".

---

# 3. Migrenownik

Cel

Pomóc użytkownikowi odzyskać kontrolę nad własną migreną.

Najważniejsze funkcje

- rejestrowanie napadów
- objawy
- leki
- wyzwalacze
- raport

Portal ma prowadzić użytkownika do Migrenownika.

Migrenownik ma prowadzić użytkownika z powrotem do wiedzy.

---

# 4. Neurolodzy

Cel

Pomóc znaleźć lekarza zajmującego się leczeniem migreny.

Na początku

- lista polecanych specjalistów
- wyszukiwarka
- informacje o przygotowaniu do wizyty

W przyszłości

Program partnerski dla gabinetów neurologicznych.

---

# 5. O projekcie

Cel

Budowanie zaufania.

Najważniejsze elementy

- Dlaczego powstała Pani Migrena
- Manifest
- Misja
- Wartości

Nie opisujemy firmy.

Opisujemy ideę.

---

# 6. Newsletter

Cel

Utrzymywanie spokojnego kontaktu z użytkownikiem.

Newsletter nie służy sprzedaży.

Służy wspieraniu.

---

# 7. Kontakt

Cel

Umożliwienie kontaktu z zespołem.

Kategorie kontaktu

- pytania
- współpraca
- media
- gabinety neurologiczne

---

# Relacje pomiędzy elementami

Każda część portalu prowadzi do kolejnego kroku.

Strona główna
↓
Wiedza
↓
Migrenownik
↓
Neurolog
↓
Powrót do Wiedzy

Nie istnieją ślepe zaułki.

---

# Nawigacja główna

- Wiedza
- Migrenownik
- Neurolodzy
- O projekcie

Kontakt i Newsletter pozostają elementami pomocniczymi.

---

# Zasady architektury

1. Człowiek jest ważniejszy niż produkt.

2. Każda strona ma jeden główny cel.

3. Każda strona prowadzi do następnego kroku.

4. Nie projektujemy chaosu.

5. Nie projektujemy pod SEO.

Projektujemy dla człowieka.

SEO jest konsekwencją jakości.

6. Portal i Migrenownik są jednym ekosystemem.

Nie dwoma osobnymi produktami.

---

# Poza zakresem MVP

Nie planujemy w wersji 1.0:

- forum
- czatu
- kont premium
- reklam
- sponsorowanych artykułów
- sklepu

Te elementy mogą zostać rozważone dopiero wtedy, gdy będą wspierały misję projektu.

---

# Kryterium sukcesu

Osoba odwiedzająca portal po raz pierwszy:

1. czuje się zrozumiana,
2. ufa marce,
3. znajduje odpowiedź na swoje pytanie,
4. wykonuje kolejny krok bez zastanawiania się, gdzie kliknąć.
