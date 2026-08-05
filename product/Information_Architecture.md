# Information Architecture v1

## Status

Draft v1

---

# Cel

Pani Migrena jest miejscem internetowym, które pomaga użytkownikowi odnaleźć właściwą przestrzeń zgodnie z jego aktualną potrzebą.

Architektura została zaprojektowana wokół potrzeb użytkownika, a nie kategorii medycznych.

---

# Główna architektura

```
Home (Przedsionek)

├── Chcę zrozumieć
├── Poznaj siebie
└── Żyć pełniej (nazwa robocza)
```

---

# Model organizacji treści

Pani Migrena nie organizuje treści według kategorii ani typów publikacji.

Podstawową jednostką organizacji wiedzy jest **Temat**.

Każdy temat prezentowany jest z trzech uzupełniających się perspektyw:

## 🧠 Chcę zrozumieć

Odpowiada na pytanie:

> Co warto wiedzieć?

Dostarcza rzetelnej wiedzy, wyjaśnień oraz odpowiedzi opartych na aktualnej wiedzy medycznej.

Efekt dla użytkownika:
**Odpowiedź.**

---

## 🌿 Poznaj siebie

Odpowiada na pytanie:

> Jak wygląda to u mnie?

Pomaga użytkownikowi obserwować własne doświadczenia, odkrywać wzorce oraz korzystać z Migrenownika jako narzędzia wspierającego poznawanie siebie.

Efekt dla użytkownika:
**Odkrycie.**

---

## 🌞 Żyć pełniej

Odpowiada na pytanie:

> Jak mogę żyć pełniej pomimo migreny?

Pokazuje doświadczenia innych osób, inspiracje oraz praktyczne sposoby odzyskiwania przestrzeni na codzienne życie.

Efekt dla użytkownika:
**Inspiracja.**

---

Każdy istotny temat w serwisie powinien być projektowany z uwzględnieniem wszystkich trzech perspektyw.

---

# Home (Przedsionek)

## Cel

Pomóc użytkownikowi odnaleźć właściwy kierunek.

Home nie prezentuje całego serwisu. Jest spokojnym wejściem do miejsca.

## Zawiera

* Hero
* Trzy główne wejścia
* Stopkę

## Nie zawiera

* sekcji promocyjnych,
* newslettera,
* Migrenownika,
* polecanych treści,
* elementów typu CTA.

---

# Przestrzeń 1 — Chcę zrozumieć

## Cel

Pomóc użytkownikowi znaleźć odpowiedzi na pytania dotyczące migreny.

## Zasady

* Nawigacja oparta jest na pytaniach użytkownika.
* Nie stosujemy klasycznych kategorii wiedzy.
* Treści prowadzą do kolejnych pytań i tworzą ścieżki zrozumienia.

## Efekt

Użytkownik wychodzi z odpowiedzią.

---

# Przestrzeń 2 — Poznaj siebie

## Cel

Pomóc użytkownikowi odkrywać własne wzorce i lepiej rozumieć swoje doświadczenia.

## Zasady

* Migrenownik jest narzędziem, a nie głównym produktem.
* Obserwacja prowadzi do odkrywania, a nie wyłącznie zbierania danych.
* Migrenownik nie jest elementem głównej nawigacji.

## Efekt

Użytkownik wychodzi z odkryciem.

---

# Przestrzeń 3 — Żyć pełniej *(nazwa robocza)*

## Cel

Pomóc użytkownikowi odzyskiwać przestrzeń na życie pomimo migreny.

## Zakres

* praca,
* rodzina,
* relacje,
* podróże,
* planowanie,
* poczucie winy,
* odpoczynek,
* codzienność.

## Efekt

Użytkownik wychodzi z rozwiązaniem lub pomysłem, który może wykorzystać w swoim życiu.

---

# Zasady architektury

* Home pełni rolę przedsionka.
* Produkt składa się z trzech głównych przestrzeni.
* Architektura opiera się na potrzebach użytkownika, nie na strukturze medycznej.
* Historie użytkowników oraz elementy wspierające są obecne w całym serwisie, a nie jako osobna przestrzeń.
* Migrenownik jest częścią ekosystemu, ale nie jest centralnym elementem produktu.

---

# Otwarte decyzje

* Ostateczne nazwy trzech głównych przestrzeni.
* Treść Hero.
* Wizualna interpretacja motywu „drzwi”.

