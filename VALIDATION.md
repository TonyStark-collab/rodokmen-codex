# Ověření verze 1.0.0 (28. 10. 2026)

Provedeno v této relaci na Linuxu s Pythonem 3.12 a Node.js 24:

- Parsování manifestu, YAML metadat skillu a všech JSON souborů; kontrola přítomnosti komponent.
- Syntaktická kontrola všech přibalených Python souborů.
- Založení projektu do cesty s mezerami, nápověda inicializátoru a přítomnost `AGENTS.md`.
- Aktualizace projektu: původní rodinná data zůstala zachována, upravený web a nástroj byly zálohovány.
- Kontrola dat správně odmítla prázdný projekt bez výchozí osoby a přijala doplněnou vymyšlenou osobu.
- Import malého vymyšleného GEDCOM: dítě, otec, matka a český formát data.
- Kontrola přibaleného ukázkového rodokmenu: bez chyb.
- Export ukázkových dat do webu: dokončen.
- `npm ci`, `npm run data` a `npm run build`: dokončeno; Astro sestavilo 587 stránek a Pagefind vytvořil vyhledávání.

Nebyla prováděna nová genealogická rešerše ani ověření přístupu ke všem archivům.
Ukázkové osoby jsou vymyšlené. Sestavení není vizuální kontrola všech stránek ani potvrzení historických závěrů.
