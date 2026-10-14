---
name: workshop-zapis
description: Zápis z callu, schůzky nebo workshopu a follow-up pro účastníky — z přepisu (VTT, TXT, MD), poznámek a případně screenshotů z Mira nebo FigJamu. Umí tři režimy — krátký zápis na jednu stranu (rozhodnutí s doslovnou citací, úkoly, otevřené otázky), follow-up k odeslání (jen návrh, nic neodesílá) a plný analytický zápis z workshopu (slovník, hypotézy a otevřené otázky jako podklad pro další fáze projektu). Použij VŽDY, když uživatel chce zápis nebo shrnutí z callu, schůzky, porady či workshopu („udělej zápis z tohoto callu“, „zápis ze schůzky“, „napiš follow-up po callu“, „shrň workshop“, „mám transkript a Miro screenshoty“), nebo nahraje přepis pracovního setkání. **Zápis z tréninku, kurzu nebo přednášky je jiná úloha** (narativní, s anonymizací účastníků); na něj tenhle skill nepoužívej.
---

# Zápis z callu, schůzky nebo workshopu

Z přepisu a dalších materiálů z pracovního setkání vyrobíš jeden ze tří výstupů. Který, určíš v kroku 0.

| Režim | Kdy | Co vznikne |
|---|---|---|
| **Krátký zápis** | výchozí u callu a schůzky | nejvýš jedna strana: rozhodnutí s doslovnou citací, úkoly, otevřené otázky a neshody, mezery v záznamu |
| **Follow-up** | když uživatel chce follow-up nebo shrnutí pro účastníky | návrh zprávy k odeslání: krátké shrnutí a další kroky; nic se neodesílá |
| **Plný zápis** | workshop s artefakty (nástěnka, breakouty, metodika) | strukturovaný analytický zápis, viz níže |

**Plný zápis** z **klientského strategického nebo designového workshopu** slouží jako pracovní podklad pro další fáze projektu (sense-making, strategie, IA, skici, copy). Zápis se nečte jako vyprávění — slouží jako **referenční katalog faktů, citací, slovníku, hypotéz a otevřených otázek**, ze kterého se v dalších fázích vytahují konkrétní podklady.

> **Když je to trénink, kurz nebo přednáška**, je to jiná úloha: narativní zápis s anonymizací účastníků a hlavními tezemi, ne analytický katalog. Tenhle skill na ni nepoužívej.

## Zásady pro všechny režimy

Režimy se liší rozsahem a tvarem, zásady mají stejné:

- **Citace** jsou doslovné, v uvozovkách a s mluvčím: jménem, nebo rolí, když jméno nezaznělo (krok 4 a `references/role-a-jmena.md`).
- **Spor** — kde se účastníci nedohodli — patří do otevřených otázek, ne mezi rozhodnutí (krok 3).
- **Mezery v záznamu** označ (krok 4).
- **Nic nedomýšlej.** Co ve vstupu není, označ jako neznámé; lepší explicitní mezera než dohad.
- **Role a disambiguace jmen** podle `references/role-a-jmena.md`.

## Reference podle režimu

Po volbě režimu (krok 0) si načti:

| Režim | Načti |
|---|---|
| Krátký zápis | `references/kratky-zapis.md`, `references/role-a-jmena.md` |
| Follow-up | `references/follow-up.md`, `references/kratky-zapis.md` (oddíl „Rozhodnutí, úkoly a termíny“), `references/role-a-jmena.md` |
| Plný zápis | všechny čtyři níže |

- `references/struktura-zapisu.md` — frontmatter, osa, délka, co dovnitř a co ne
- `references/typy-workshopu.md` — Lean Canvas / VPC / AARRR / Future scenarios / Customer Journey — jak strukturovat zápis podle typu
- `references/prace-s-mirem.md` — jak číst Miro / FigJam screenshoty (lepíky, dot voting, červené kroužky, šipky)
- `references/role-a-jmena.md` — jmenovité role, disambiguace duplicitních jmen, klíč pro budoucí čtenáře

## Hlavní rozdíl plného zápisu proti zápisu z tréninku

| Aspekt | Zápis z tréninku nebo přednášky | Plný zápis |
|---|---|---|
| **Účel** | Sdílet, archivovat — čte se jako dokument | Pracovní podklad pro další fáze projektu |
| **Forma** | Narativní (plynulý text) | Hybridní (sekce + katalog + citace + tabulky) |
| **Účastníci** | Anonymizovaní | **Jmenovitě s rolemi** |
| **Citace** | Vybrané, vsazené v textu | **Doslovné, často** — klient kraje sám sebe |
| **Slovník klienta** | Definice rozpuštěné v textu | **Samostatná sekce** (slovník = surovina pro IA, copy) |
| **Hypotézy / otevřené otázky** | Nejsou | **Samostatné sekce** — krmí sense-making a strategii |

## Co potřebuješ jako vstup

**Krátký zápis a follow-up:** přepis nebo poznámky z callu či schůzky (povinné), datum a účastníci s rolemi. Když přepis uvádí jen role mluvčích, stačí role a jména označ k doplnění (`references/role-a-jmena.md`). Doptej se, jen když nepoznáš ani role mluvčích. Screenshoty, typ workshopu ani osnovu nepotřebuješ.

**Plný zápis z workshopu:**

1. **Transkript** (povinné, pokud je k dispozici) — `.vtt` titulky, `.txt` přepis nebo `.md` poznámky. Pokud transkript neexistuje, pracuj jen ze screenshotů (delivery bude omezenější — flagni v zápisu).
2. **Screenshoty z Mira / FigJamu / fyzické nástěnky** (často klíčové — workshopy mají hodnotu vizuálních artefaktů, které transkript nezachytí). Pokud screenshoty nemáš, ale workshop měl breakout fáze nebo silnou vizuální složku, **doptej se**.
3. **Metadata workshopu**:
   - **Projekt a klient** (název klienta)
   - **Číslo / pořadí** (WS1 / WS2 / sense-making / revize skic…)
   - **Typ workshopu** (strategický, VPC, Lean Canvas, AARRR, Future scenarios, Customer Journey, sense-making…)
   - **Datum a délka**
   - **Facilitátoři** (facilitační tým — kdo vedl, kdo asistoval)
   - **Účastníci klienta** **jmenovitě s rolemi** — bez nich nemůžeš správně přiřadit citace ani disambiguovat duplicitní jména. Pokud máš e-mail od klienta s rolemi, použij ho jako zdroj.
4. **Případně osnova** — pokud existuje (HoŘ ji typicky chystá pro klienta v anotaci workshopu).

**Pokud chybí účastníci s rolemi nebo aspoň jeden zdroj (transkript / screenshoty), doptej se. Špatně přiřazená citace nebo zaměněný účastník je horší než žádný zápis.**

## Postup práce

### 0. Vyber režim

1. **Zadání režim jmenuje** — platí zadání. „Follow-up“, „shrnutí pro účastníky“, „co poslat po callu“ → follow-up. „Krátký zápis“, „zápis z callu / ze schůzky / z porady“ → krátký zápis. „Plný / analytický zápis“ nebo zápis z workshopu s nástěnkou či breakouty → plný zápis. Název skillu (`workshop-zapis`) režim neurčuje.
2. **Zadání režim nejmenuje** — rozhodni podle vstupu. Přepis nebo poznámky z callu či schůzky → **krátký zápis** (výchozí). Workshop s artefakty (screenshoty z Mira / FigJamu, breakouty, metodika z `references/typy-workshopu.md`) → **plný zápis**.
3. **Zadání a vstup si odporují nebo to nejde poznat** (např. „shrň workshop“ jen s krátkým přepisem) → polož jednu otázku s možnostmi a počkej na odpověď: *„Co z toho mám udělat? 1) krátký zápis na jednu stranu, 2) follow-up pro účastníky k odeslání, 3) plný analytický zápis z workshopu — nebo napiš vlastními slovy.“*

Chce-li uživatel zápis i follow-up, udělej nejdřív krátký zápis a follow-up postav na něm. Zvolený režim řekni jednou větou na začátku („Dělám krátký zápis z callu.“), ať ho uživatel může změnit.

Kroky 2, 3 a 6 platí pro všechny režimy, krok 1 jen pro plný zápis. V krocích 4 a 5 se krátký zápis a follow-up řídí svou šablonou.

### 1. Pochop typ workshopu a strukturu

Z `references/typy-workshopu.md` vyber, jaké sekce má zápis mít. Typické šablony:

- **Strategický (byznys model + Future/Anti-future + AARRR + cíl):** byznys model → ideální vs. noční scénáře → AARRR funnel → hlavní cíl + metriky → strategická zjištění → hypotézy → otevřené otázky.
- **VPC + Customer Journey** (zákazníci): potřeby → řešení → alternativy → USP → hodnota pro zákazníka → zákaznické segmenty (gains/pains/journey pro každý) → důvěryhodnost → use cases → slovník → hypotézy.
- **Sense-making:** insighty z výzkumu → segmentace → příležitosti → strategické otázky pro další fáze.
- **Customer Journey workshop** (samostatný): segmenty → journey per segment → moments of truth → friction points → příležitosti.

Pokud workshop nezapadá do žádné šablony, postav strukturu podle obsahu, ale **drž obecnou kostru:** frontmatter → TL;DR → kontext → tematické sekce → slovník → hypotézy → otevřené otázky.

### 2. Načti vstupy

- **Transkript** — přečti celý, vstřebej tok diskuze, identifikuj hlavní hlasy, klíčové citace, body shody / sporu.
- **Screenshoty** — popiš lepíky textově, zachyť dot voting (počty hlasů), červené kroužky / zvýraznění (= prioritizované položky), šipky a vztahy mezi lepíky.
- **E-mail s účastníky** — vytvoř si tabulku „kdo má jakou roli a co přináší do debaty".

### 3. Identifikuj klíčové prvky

Při čtení sleduj a poznamenej si:

- **Klíčové strategické závěry** — co z workshopu vyjde jako směrodatné pro projekt
- **Body shody** (kde se účastníci shodli) vs. **body sporu** (kde se nedohodli — tyto musí být v zápisu jako otevřené otázky)
- **Klíčové citace doslova** — když klient sám sebe kraje, drž v uvozovkách
- **Slovník klienta** — jak mluví o sobě, o zákaznících, o produktech, o konkurenci. Důležité pro IA, navigaci, copy.
- **Konkrétní příběhy a use cases** — anekdoty z praxe, které poslouží jako podklad pro skici a copy
- **Hypotézy k ověření v dalším výzkumu** — to, co účastníci tvrdí, ale je to třeba potvrdit
- **Otevřené strategické otázky** — co se v debatě neuzavřelo

### 4. Napiš zápis

**Krátký zápis** piš podle `references/kratky-zapis.md`, **follow-up** podle `references/follow-up.md`.

**Plný zápis:** drž osu z `references/struktura-zapisu.md`. Klíčové prvky:

- **Frontmatter** s plnými metadaty (projekt, datum, délka, facilitátoři, účastníci s rolemi, zdroje, **disambiguace duplicitních jmen** — viz `references/role-a-jmena.md`)
- **TL;DR** s 5–10 větami — hlavní strategické závěry, klíčové insighty, body sporu, mezery v záznamu (pokud existují)
- **Tematické sekce** podle typu workshopu (`references/typy-workshopu.md`)
- **Slovník** klienta — samostatná sekce
- **Konkrétní příběhy a use cases** — samostatná sekce, doslovně nebo téměř doslovně
- **Hypotézy k ověření v dalším výzkumu** — číslované
- **Otevřené strategické otázky** — pro sense-making a strategii
- **Atmosféra a meta-pozorování** (volitelně) — z kola „s čím odcházíte" / signály o stavu firmy

Další dva odstavce platí ve všech třech režimech. Když jméno nezaznělo, místo něj stojí role z přepisu.

**Citace pište jmenovitě.** Klient = identifikovatelný hlas, ne anonymní účastník. Pokud někdo řekl něco silného, identifikujte kdo: *„[Jméno Příjmení] ([Klient]): zákazníci nás dnes najdou hlavně přes doporučení, web je až druhý krok."* (ilustrační příklad)

**Mezery v záznamu** (např. breakout fáze, kde transkript chybí) **flagujte explicitně** — *„Mezera v transkriptu (1:43–2:27, ~44 min) — chybí celá breakout fáze, kdy se mapovaly oba segmenty."* Pokud máte ze screenshotů co doplnit, doplňte. Pokud ne, popište, co o té fázi víme z toho, jak ji facilitátor uvedl a uzavřel.

### 5. Lint — zkontroluj sám sebe

Krátký zápis a follow-up zkontroluj podle oddílu „Hotovo když“ v jejich šabloně. Plný zápis takhle:

Před odevzdáním projdi checklist:

- [ ] Frontmatter má projekt, datum, délku, facilitátory, účastníky s rolemi
- [ ] **Disambiguace duplicitních jmen** explicitně vyřešena (typický případ: dva lidé se stejným křestním jménem, jeden u klienta a druhý ve facilitačním týmu)
- [ ] TL;DR shrnuje strategické závěry workshopu, ne výčet aktivit
- [ ] Citace jmenovitě, doslovně v uvozovkách
- [ ] Slovník klienta je samostatná sekce
- [ ] Hypotézy a otevřené otázky jsou číslované a akční
- [ ] Mezery v záznamu jsou flagnuté
- [ ] Strategická zjištění (co z toho plyne pro projekt) jsou explicitně formulovaná
- [ ] **Žádná anonymizace** — workshop je pracovní materiál, nejde o sdílení mimo projekt

### 6. Ulož

Všechny výstupy patří do `vystupy/` v Prostoru (když složka není, ulož výstup tam, kde pracuješ, a řekni kam). Bez sufixu verze, pokud uživatel neřekne jinak.

| Režim | Název souboru |
|---|---|
| Krátký zápis | `{RRRR-MM-DD}-{tema}-zapis.md` podle data callu (např. `2026-03-10-cenik-zapis.md`) |
| Follow-up | `{RRRR-MM-DD}-{tema}-follow-up.md` |
| Plný zápis | `WS{N}-{tema}-zapis.md` (např. `WS1-strategicky-zapis.md`, `WS2-zakaznici-zapis.md`) |

**Follow-up je návrh.** Ulož ho a ukaž uživateli; odeslání nech na něm. Sám ho neodesílej ani nevkládej do e-mailu, chatu nebo kalendáře, ani když k nim máš přístup.

Pokud existují **screenshoty z Mira**, neukládej je — **flagni je v zápisu jako zdroj** (frontmatter `zdroje:`) a doporuč uživateli, ať si je uloží na Drive nebo do `sources/` v Prostoru.

## Co skill NEdělá

- Nepřepisuje audio na text (předpokládá hotový transkript nebo VTT)
- Nehledá materiály na Drive (to je samostatná úloha discovery)
- Negeneruje sense-making artefakty (persony, JTBD, opportunity areas) — to je samostatná úloha sense-makingu
- Negeneruje strategii, IA návrh, skici — workshop zápis je vstup, ne výstup těchto fází
- Neupravuje hotový zápis podle externích komentářů (jiný workflow)
- Neodesílá follow-up ani zápis — připraví návrh, odeslání je na uživateli
