[Strona główna](../../README.md) > [Dokumentacja](../README.md) > [ADR](README.md) > [ADR 0001](0001-srd-markdown-compilation.md)

---

# ADR 0001: Kompilacja Podręczników PHB/DMG z Rozproszonych Źródeł Markdown

* **Status:** Zaakceptowany
* **Data:** 2026-07-10
* **Autorzy:** Kacper Czeczot

---

## Kontekst
Zasady Dungeons & Dragons 5e (SRD 5.2.1 oraz wersja 2024) pochodzą z wielu źródeł: oficjalnego dokumentu SRD, zrzutów wikidot oraz materiałów Unearthed Arcana (UA). Potrzebny był spójny system kompilacji pełnych podręczników w języku angielskim i polskim.

## Decyzja
1. **Markdown jako Standard Bazy:** Wszystkie moduły, czary, bestie i klasy przechowywane są w czystym formacie Markdown.
2. **Słowniki Tłumaczeń w `docs/glossary/`:** Jednoznaczne mapowanie nazw czarów, klas, cech i terminów mechaniki.
3. **Automatyczne Generatorzy w `scripts/`:** Skrypty kompilujące kompletny *Player's Handbook* i *Dungeon Master's Guide* do `data/compiled/`.

## Konsekwencje
### Pozytywne:
- Możliwość generowania jednolitych, zintegrowanych podręczników w Markdown.
- Pełna spójność terminologiczna pomiędzy wersją EN a PL.
