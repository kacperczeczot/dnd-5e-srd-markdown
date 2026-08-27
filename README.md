# D&D 5e SRD & 2024 Rules Markdown

> Kompletna baza wiedzy, zbiór reguł System Reference Document 5.2.1 oraz edycji D&D 2024 w formacie Markdown (wersje EN i PL), słowniki terminologiczne oraz kompilator podręczników.

---

## 1. Zasady i Dokumentacja


| Dokument / Sekcja | Opis |
| :--- | :--- |
| [Baza Dokumentacji (`docs/README.md`)](docs/README.md) | Centralny hub dokumentacyjny projektu |
| [Słowniki Tłumaczeń (`docs/glossary/`)](docs/glossary/czary-tlumaczenie.md) | Mapowanie nazw czarów, podklas i terminologii mechaniki |
| [Zasady SRD 5.2.1 (`docs/srd-5.2.1/`)](docs/srd-5.2.1/) | Oficjalny zbiór reguł SRD 5.2.1 |
| [D&D 2024 Wikidot PL (`docs/dnd2024-wikidot-pl/`)](docs/dnd2024-wikidot-pl/) | Polskie tłumaczenie kompendium D&D 2024 |
| [Reguły AI Projektu (`.agents/rules/project.md`)](.agents/rules/project.md) | Wytyczne domenowe dla asystentów AI |

---

## 2. Mapa Repozytorium

* 📁 [**`docs/`**](docs/README.md) — Kompendium zasad (SRD 5.2.1, wikidot EN/PL), słowniki tłumaczeń i ADR.
* 📁 [**`data/`**](data/README.md) — Skompilowane podręczniki (`compiled/`) oraz materiały źródłowe (`sources/`).
* 📁 [**`scripts/`**](scripts/README.md) — Skrypty budowania podręczników i ujednolicania terminologii.

---

## 3. Uruchomienie i Kompilacja

```bash
# Kompilacja Podręcznika Gracza 2024 PL
python3 scripts/build_players_handbook.py

# Kompilacja Przewodnika Mistrza Podziemi 2024 PL
python3 scripts/build_dungeon_masters_guide.py
```
