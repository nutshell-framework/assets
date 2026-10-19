# Changelog

## 2.0.18 (19.10.2026)

- Grid: `.row-{n}` und `.row-{bp}-{n}` als Kurzform zu `.row-span-*` ergänzt
- Grid: `.content-grid` erhält dieselben Grid-Styles wie `.row`
- neue Mixins `make-row-span()` und `make-row-start()`
- neues Mixin `make-grid()` ersetzt `make-row()`; `make-row()` ist deprecated und leitet an `make-grid()` weiter
- Mixin `make-offset()` entfernt (seit Langem deprecated und ohne Funktion), bestehende Aufrufe müssen entfernt werden

## 2.0.17 (23.09.2026)

- Lizenzangabe in den Dateiköpfen auf LGPL-3.0-or-later korrigiert (passend zur `composer.json`)

## 2.0.16 (28.08.2026)

- Accordion (Contao 5.3+): `border-top` am Inhaltsbereich entfernt, den Contao standardmäßig setzt

## 2.0.15 (27.08.2026)

- Vorbereitung auf Dart Sass 2: Slash-Divisionen durch `calc()` ersetzt (kompatibel mit scssphp)
- Fallbacks für Browser ohne Grid-Support (`@supports not (display: grid)`) entfernt
- `make-width()`: Fallback ohne `calc()` entfernt
- wirkungslose `-ms-`-Eigenschaften entfernt
- `grid-gap`, `grid-column-gap` und `grid-row-gap` auf `gap`, `column-gap` und `row-gap` umgestellt
- Accordion (Contao 5.3+): `border-bottom` entfernt, den Contao standardmäßig setzt

## 2.0.14 (12.06.2026)

- Youtube: Anker-Anweisung entfernt, da es sonst zu Problemen mit Contao Consent und Co. kommen kann

## 2.0.13 (24.01.2025)

- Custom Property `--buton-font-size` ergänzt

## 2.0.12 (01.11.2024)

- Tippfehler behoben

## 2.0.11 (24.10.2024)

Usability-Verbesserungen:

- Custom Property --links-color-visited für besuchte Links
- Custom Property --links-outline-focus für fokussierte Links

## 2.0.10 (06.03.2024)

- newsletter subscribe/unsubscribe: fix captcha when visible
- newsletter subscribe/unsubscribe: fix channel checkboxes when activated

## 2.0.9 (16.02.2024)

- add support for new contao 5.3 nested elements

## 2.0.8 (20.12.2023)

- update `invisible` class styles and mixin

## 2.0.7 (11.12.2023)

- remove outdated css classes for search forms
- fix youtube preview image (and 3rd-party notes)

## 2.0.5 / 2.0.6 (20.11.2023)

- add custom properties for button border-style and border-color
- add handorgel accordion support

## 2.0.3 / 2.0.4 (14.03.2023)

- fix content-gallery list style options

## 2.0.2 (13.03.2023)

- add contao 5 content element classes, e.g. `content-text`

## 2.0.1 (17.01.2023)

- optimize headings
