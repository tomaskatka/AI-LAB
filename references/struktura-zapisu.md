# Struktura zápisu z klientského workshopu

Standardní osa. Drž se jí — variace povolené, ale s důvodem v obsahu, ne v náladě.

> Jména, citace a obsah v ukázkách v tomto souboru jsou ilustrační (vymyšlené).

## Frontmatter

YAML hlavička s metadaty:

```yaml
---
projekt: {Klient} — {typ projektu}
typ: zápis ze strategického workshopu
číslo: WS{N} ({krátký název})
datum: 2026-MM-DD
délka: {h:mm}
facilitátoři: {jméno facilitátora} · {jméno co-facilitátora, pokud byl}
účastníci klient: {jméno} ({role}) · {jméno} ({role}) · ... ({počet})
zdroje:
  - {cesta k transkriptu / VTT}
  - Miro nástěnka — {N} screenshotů
  - e-mail / dokument s anotací workshopu
---
```

**Disambiguace duplicitních jmen** — pokud na workshopu jsou 2 nebo více lidí stejného jména (typicky facilitátor a člověk z klienta se stejným křestním jménem), zapiš to explicitně do frontmatteru jako poznámku:

```yaml
účastníci klient: Petr Novák (obchodní ředitel — jiný Petr než facilitátor) · Petr Svoboda (vedoucí servisu) · ...
```

A v textu pak přidej krátký vysvětlující odstavec za frontmatter: *„Pozor: na workshopu byli 3× Petr — Petr Novák (klient, obchodní ředitel) · Petr Svoboda (klient, vedoucí servisu) · Petr Dvořák (facilitátor). Všechny zmínky 'Petr z {klient}' v textu = Petr Novák (klient)."*

## Osa zápisu

### 1. Title (H1, většinou implicitní z frontmatteru)

Není povinný — frontmatter už nese identifikaci. Ale pokud chceš, krátký věcný:
```markdown
# WS2 — Strategický workshop: Zákazníci [Klient]
```

### 2. Krátký kontextový blockquote (povinný)

Jedna věta pod frontmatterem. Co byl workshop, jakou metodikou, kolik lidí.

```markdown
> Druhý strategický workshop projektu, zaměřený na value proposition canvas — kdo jsou zákazníci [Klient], co potřebují, jak to dnes řeší a v čem je [Klient] unikátní oproti alternativám.
```

### 3. TL;DR (povinné)

5–10 vět. **Hlavní strategické závěry** workshopu, ne výčet aktivit. Pokud existují **klíčové insighty** (něco, co změní směr projektu), uveď je explicitně. Pokud jsou v záznamu **mezery** (chybějící breakout fáze, ztracená audio kvalita), uveď to v TL;DR.

Špatně: *„Probrali jsme byznys model, AARRR funnel a stanovili metriky."*
Dobře: *„Hlavní cíl projektu je *Zákazník najde odpověď dřív, než musí volat* — strategický posun: web jako samoobslužný průvodce, ne katalog. Opakované zakázky tvoří většinu obratu, ale web mluví jen k novým zákazníkům — explicitní strategická díra. Největší rizika projektu jsou organizační, ne technická."*

### 4. Kontext a struktura workshopu (povinné)

Co byl cíl workshopu (z anotace klienta nebo HoŘ), jaké aktivity se postupně odehrály, jaké materiály vznikly, kde jsou mezery v záznamu.

Pokud jsou účastníci nestejně známí (různé role v různých divizích), tabulka „kdo přináší jaký pohled":

```markdown
| Osoba | Role | Co přináší |
|---|---|---|
| Petr Novák | Obchodní ředitel | ... |
| Eva Horáková | Vedoucí zákaznické podpory | ... |
```

### 5. Tematické sekce podle typu workshopu (povinné)

Viz `typy-workshopu.md` — vyber šablonu podle metodiky workshopu (Lean Canvas / VPC / AARRR / Future scenarios / Customer Journey / Sense-making).

V každé sekci:

- **Krátký kontext** sekce (1–2 věty)
- **Klíčový obsah** strukturovaně (lepíky, hlasování, vztahy)
- **Klíčové citace** doslova v uvozovkách s identifikací mluvčího
- **Drobné napětí / debata**, pokud byla — kdo jaký pohled, kde se shodli
- **Implikace pro projekt** (volitelně, pokud jsou jasné)

### 6. Slovník (povinné)

Samostatná sekce — terminologie klienta. Surovina pro IA, navigaci, copy. Strukturovaně podle kategorie:

```markdown
## Slovník (terminologie klienta)

**Klient o sobě:**
- „poradce" (preferují před „prodejce")
- „postaráme se o všechno"
- ...

**O zákaznických typech:**
- „stálí zákazníci"
- „firmy" × „domácnosti"
- ...

**O technice / produktech:**
- ...

**Specifické zkratky:**
- **ZP** = zákaznický portál (interní název, zákazníci ho tak neznají)
- **CRM {název systému}** = ...

**Negativní termíny (čemu se chceme vyhnout):**
- „tlačit do nákupu"
- ...
```

### 7. Konkrétní příběhy a use cases (volitelné, ale doporučené)

Anekdoty z praxe, které účastníci uvedli — surovina pro skici, copy, příběhy. Doslovně nebo téměř doslovně.

```markdown
- **Majitel menší firmy**, který si nabídku vytiskl, podtrhal, čemu nerozuměl (a pak zavolal konkurenci, která mu to vysvětlila).
- **Nákupčí** s nachystaným podkladem pro vedení (srovnání + cena + příběh proč).
- ...
```

### 8. Hypotézy k ověření (povinné)

Číslovaný seznam hypotéz, které z workshopu vyšly a je třeba je potvrdit / vyvrátit ve výzkumu nebo dalších fázích.

```markdown
1. **{Stručná formulace hypotézy}** — {kontext, kde to v workshopu padlo, proč to ověřit}.
2. ...
```

### 9. Otevřené strategické otázky (povinné)

Pro sense-making, strategii a další fáze. Otázky, které se v workshopu **neuzavřely** — kdo s kým co nesouhlasil, kde scope není jasný, jaké rozhodnutí je třeba udělat.

```markdown
1. **Samoobsluha vs. osobní kontakt** — má web vést zákazníka k řešení bez telefonu, nebo k rozhovoru s obchodníkem?
2. ...
```

### 10. Atmosféra a meta-pozorování (volitelné)

Z kola „s čím odcházíte", signály o stavu firmy / týmu, frustrace z minulých projektů, ochota týmu spolupracovat. Tyto signály jsou důležité pro **interní strategii projektu** (jak komunikovat, jaké riziko ohledně change managementu).

## Délka

Workshop zápis bývá **delší než zápis z tréninku**, protože udržuje katalog dat (slovník, citace, hypotézy) — není to destilace, ale strukturovaná organizace.

| Délka workshopu | Cílová délka zápisu |
|---|---|
| 4 h + breakouty | 5000–7000 slov |
| 2–3 h | 3500–5000 slov |
| 90 min | 2000–3000 slov |

Délka je vodítko, ne dogma. Pokud workshop měl bohaté Miro nástěnky s hodně daty, smí být zápis na horní hraně. Prázdná místa nevycpávej.

## Co do zápisu nepatří

- **Anonymizace** — klient = jmenovité role.
- **Marketingová tonalita** („Inspirativní setkání plné poznatků") — věcně, faktograficky.
- **Hodnocení průběhu** („Diskuze byla velmi živá") — fakta, ne soudy.
- **Časové štítky** („V čase 1:23:45 padlo") — jen pokud nesou významnou informaci (např. mezera v záznamu).
- **Doslovné delší pasáže přepisu** — citujte krátké, výstižné. Delší debaty parafrázujte.
- **Detail organizace setkání** (přestávky, technické problémy) — kromě těch, které ovlivňují kvalitu zápisu (mezery v záznamu).
