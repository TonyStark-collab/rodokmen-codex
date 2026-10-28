# Původ a změny

- Zdroj: https://github.com/sarsonj/rodokmen-skill
- Autor zdrojového projektu: Jindřich Šaršon.
- Převzatý commit: `a9bbdade916293d6dd3be640a23e7c10cab96849` (upstream verze 0.5.0).
- Adaptace vytvořena pro Tonyho na jeho žádost dne 28. 10. 2026; verze balíčku 1.0.0.
- Archivní nástroje, datové formáty, části referencí a šablona Astro jsou převzaté a upravené
  za podmínek MIT. Původní licenční text je v `LICENSE` u skillu i v kořeni balíčku.
- `reference/playbook.md` z původního projektu není pod MIT a nebyl převzat.
  Odkazy na něj byly nahrazeny vlastní metodikou `reference/metodika.md`.
- `SKILL.md` byl přepracován pro Codex: dostupné nástroje, navazování v projektu,
  žádný povinný úvodní rozhovor, doložení vztahů a jednotlivých tvrzení, práce s nejistotou,
  rozlišení vzpomínky, cizího stromu a přímého pramene.
- Projekt používá `AGENTS.md`; integrace `.claude` a povinné modely Claude byly odstraněny.
  Inicializátor má argumenty argparse, skutečnou nápovědu a zálohy upravených nástrojů i webu.
- Přidán `data/vazby.md`, vlastní důkazní metodika a metadata skillu pro Codex.
- Odstraněny instrukce k automatickému připomínání zasílání zpětné vazby původnímu autorovi.
- Neobsahuje skutečné rodinné údaje uživatele, MCP server, přihlašovací údaje ani automatické hooky.

Ověření sestavení a místních nástrojů není ověřením správnosti historických nálezů
ani dnešní dostupnosti všech archivních portálů. Ty se ověřují při konkrétním hledání.
