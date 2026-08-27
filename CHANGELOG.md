# Dziennik Zmian (Changelog)

Wszystkie istotne zmiany w projekcie są dokumentowane w tym pliku zgodnie ze standardem [Keep a Changelog](https://keepachangelog.com/pl/1.1.0/) oraz [Semantic Versioning](https://semver.org/lang/pl/).

---

## [Unreleased]

### Added
- Dostosowanie repozytorium do standardów DevEx (Single-App).
- Struktura dokumentacji `docs/` z certyfikatem `docs/STANDARDS.md` i rejestrem `docs/adr/`.
- Pliki konfiguracyjne: `.editorconfig`, `.agents/rules/project.md`, `.github/pull_request_template.md`.

### Changed
- Reorganizacja struktury do Kanonu Root:
  - `srd-5.2.1/` ➡️ `docs/srd-5.2.1/`
  - `dnd2024-wikidot/` ➡️ `docs/dnd2024-wikidot/`
  - `dnd2024-wikidot-pl/` ➡️ `docs/dnd2024-wikidot-pl/`
  - `sources/` ➡️ `data/sources/`
  - `compiled/` ➡️ `data/compiled/`
  - `docs/*-tlumaczenie.md` ➡️ `docs/glossary/`
- Zaktualizowanie ścieżek we wszystkich skryptach w `scripts/`.

---

## [1.0.0] - 2026-07-10

### Added
- Baza reguł SRD 5.2.1 oraz zrzut zasad dnd2024 w Markdown.
- Generator skompilowanych podręczników PHB i DMG.
