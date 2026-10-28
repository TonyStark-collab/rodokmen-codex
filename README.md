# Rodokmen pro Codex

Balíček s jedním českým skillem `rodokmen` pro Codex, vytvořený na žádost Tonyho podle
MIT částí projektu [sarsonj/rodokmen-skill](https://github.com/sarsonj/rodokmen-skill).

Obsahuje pracovní návod, archivní skripty a šablonu rodinného webu. Z rodinných dokumentů
a digitalizovaných matrik pomáhá sestavit rodokmen s dohledatelnými zdroji a označenou nejistotou.

## Instalace do Codexu

1. Stáhni tento repozitář přes **Code → Download ZIP**, nebo jej naklonuj:

   ```bash
   git clone https://github.com/TonyStark-collab/rodokmen-codex.git
   ```

2. Zkopíruj celou složku `skills/rodokmen` do svého adresáře skillů v Codexu,
   například `~/.codex/skills/rodokmen/`. Pokud tam již skill stejného jména máš,
   nejprve si jej zálohuj. Zachovej i soubory `reference/`, `tools/`, `template/` a licenci.
3. Otevři novou konverzaci v Codexu a vyber skill `rodokmen`, případně jej vyvolej jménem.

K přečtení návodu není potřeba nic instalovat: začni souborem
[`SKILL.md`](skills/rodokmen/SKILL.md). Pro běh pomocných nástrojů je potřeba Python 3.9+;
pro web také aktuální Node.js podle požadavků Astro, pro výřezy ImageMagick.
Instaluj jen nástroje, které potřebuješ pro aktuální krok.

## Použití

Napiš například: „Použij skill Rodokmen. Tady je zápis o narození dědečka, hledej jeho přímé předky.“
Pokud je skill dostupný v nabídce, lze jej označit jako `$rodokmen`.
Začít lze i rodinnými informacemi nebo existujícím exportem GEDCOM.

Skill obsahuje postupy pro vyhledání a čtení matrik, přepisy a překlady, ukládání citací,
ověřování identity a příbuzenských vazeb, deník hledání a navázání v další konverzaci.
Součástí jsou archivní skripty, import GEDCOM/FTB a šablona webu s kartami osob, mapou a vějířem předků.

Přístup k archivům závisí na připojení a nástrojích konkrétní relace. Nejisté nálezy se označují;
skill negarantuje počet generací ani bezchybné čtení historického písma.

## Obsah

- `skills/rodokmen/SKILL.md`: hlavní instrukce a spouštěcí situace.
- `skills/rodokmen/reference/`: podrobné návody a vlastní důkazní metodika.
- `skills/rodokmen/tools/`: archivní a místní nástroje.
- `skills/rodokmen/template/`: nový projekt, vymyšlená ukázka a šablona Astro.
- `skills/rodokmen/PROVENANCE.md`: přesný zdroj a přehled změn; licence je MIT.

Samotný skill neobsahuje rodinná data. Ta se ukládají do samostatné složky projektu.
Tento balíček nic sám nezveřejňuje ani neposílá původnímu autorovi.

## Licence a původ

Licence [MIT](LICENSE) dovoluje používat, upravovat i dále zveřejňovat tento balíček
při zachování licenčního textu a uvedení původního autora **Jindřicha Šaršona**.
Původní projekt je [sarsonj/rodokmen-skill](https://github.com/sarsonj/rodokmen-skill),
převzatá verze odpovídá commitu `a9bbdade916293d6dd3be640a23e7c10cab96849`.

Jde o samostatnou adaptaci pro Codex: hlavní instrukce byly přepracovány, projekt používá
`AGENTS.md`, přibylo doložení jednotlivých příbuzenských vztahů a zálohování při aktualizaci.
Podrobnosti jsou v [přehledu změn](skills/rodokmen/PROVENANCE.md).

Soubor `reference/playbook.md`, na který se v původním projektu MIT nevztahuje,
**není součástí této adaptace**. Nahradila jej vlastní [metodika](skills/rodokmen/reference/metodika.md).
Výsledky místního ověření jsou v [VALIDATION.md](VALIDATION.md).
