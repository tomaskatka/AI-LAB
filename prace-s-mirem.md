# Práce s Miro / FigJam screenshoty

Workshopy mají typicky **vizuální výstup na nástěnce** (Miro, FigJam, Mural, fyzická flipchart). Screenshoty z těchto nástěnek jsou často **klíčový zdroj zápisu** — zachytávají strukturu, hlasování, vztahy, prioritu, které se z transkriptu vytahují obtížně.

> Obsah lepíků v ukázkách v tomto souboru je ilustrační (vymyšlený).

## Co na screenshotech sledovat

### Lepíky / sticky notes

Základní jednotka informace. Sleduj:

- **Obsah** — text na lepíku, doslovně
- **Barva** — typicky kódování typu obsahu:
  - **Žlutá** = neutrální / fakt / akce
  - **Zelená** = pozitivní (gains, motivace, ideální budoucnost)
  - **Růžová / červená** = negativní (pains, obavy, noční můra, friction)
  - **Modrá** = otázka / hypotéza / poznámka
  - **Oranžová / fialová** = nadpis / kategorie / segment
- **Velikost** — větší lepík obvykle = důležitější / nadpis / sumarizace
- **Pozice** — lepíky v rámečku patří k sobě, lepíky na okraji jsou outlier nebo přidané pozdě
- **Autor** — pokud je u lepíku iniciála nebo barva/styl typický pro konkrétního účastníka, atribuj

### Dot voting (hlasování tečkami)

Modré nebo fialové tečky u lepíků = **hlasování** účastníků o důležitosti / prioritě. Sleduj:

- **Počet teček** — víc teček = vyšší priorita
- **Položky bez teček** — menší / žádná priorita
- **Top 1–3 položky** — to je výsledek prioritizace, který se v zápisu zvýrazňuje (`⭐` nebo `[PRIO]`)

V zápisu uveď počet hlasů: *„Víc zákazníků se k nám vrací — 4 hlasy ⭐ (nejvíc)"*

### Červené kroužky / rámečky / zvýraznění

Manuální (facilitátor obtahuje) označení:

- **Červený rámeček kolem skupiny lepíků** = prioritizovaná skupina, klíčové scénáře, top kategorie
- **Červený kroužek u lepíku** = zvlášť důležitý prvek
- **Tlustá červená čára** = oddělení sekcí, kritická hranice

V zápisu zachycuj jako *„prioritizované scénáře"*, *„v rámečku [PRIO]"*, *„zvýrazněný moment pravdy"*.

### Šipky a vztahy

Šipky mezi lepíky = vztah / vývoj / sekvence:

- **Plná šipka** → kauzální vztah, „vede k"
- **Tečkovaná šipka** → návaznost, „pak", „později"
- **Obousměrná šipka** ↔ vzájemný vztah
- **Větvení** (1 šipka → 3 cíle) = alternativní cesty, větve customer journey

V customer journey mapách jsou šipky hlavní strukturou — popisuj je sekvenčně:

```markdown
Vstupy → Poptávka → {více větví} → Poradenství → Cenová nabídka → Nákup → Servis
```

### Černé / oranžové / barevné texty mimo lepíky

Často **nadpisy / labely sekcí**, které facilitátor přidal pro orientaci. Použij je jako názvy sekcí v zápisu:

- „Cesta službou / Customer Journey"
- „Motivace / Gains"
- „Obavy / Pains"
- „Akvizice / Aktivace / Příjmy / Retence / Doporučení"

## Jak zápis krmit ze screenshotů

### Pořiď **textový přepis lepíků** sekce po sekci

Když popisuješ sekci „Motivace / Gains", **vypiš všechny lepíky** s jejich obsahem. Strukturuj podle kategorie / barvy / pozice:

```markdown
**Motivace / Gains:**

**Důvěra v dlouhodobost a kvalitu firmy:**
- Velikost společnosti
- Desítky let prokazatelných zkušeností
- Dlouhodobost
- ...

**Profesionální přístup:**
- ...
```

### Zachyť dot voting přesně

Přidávej počet hlasů ke konkrétním lepíkům:

```markdown
**[PRIO] Klíčové cílové stavy (vybráno hlasováním):**
- ⭐ **Zákazníci si objednají servis online** — 4 hlasy (nejvíc)
- ⭐ **Máme marketingový plán postavený na datech**
- ⭐ **Víc poptávek přichází z webu** — 3 hlasy
```

### Customer journey popisuj sekvenčně

Sleduj šipky a vyjadřuj logiku:

```markdown
**Vstupy (kanály akvizice):**
- Newsletter — *nikdo ho neotevírá* ⚠️
- Veletrh
- Web — bariéra: *ceník jen na vyžádání*

→ **Poptávka** — bariéry: *dlouhá odpověď, málo práce s referencemi*

**Větve poptávky:**
- Schůzka u nás → Osobní konzultace
- E-mailová komunikace
- ...

→ **Poradenství** (bod konvergence)
→ **Cenová nabídka** → *ukázka u zákazníka*
→ **Nákup** ↔ *vyjednávání*
```

### Zvýrazňuj prioritu, mezery a otazníky

- **Klíčové prio** = `⭐` nebo `[PRIO]` nebo `**bold**`
- **Riziko / pain** = `⚠️`
- **Otevřená otázka** = `???` (z lepíku) nebo doplnění v sekci „Otevřené otázky"
- **Mezera v záznamu** = explicitní poznámka *„Tato fáze chybí v transkriptu / na screenshotech není zachycena"*

## Když screenshot je nečitelný / částečný

Stane se. **Flagni to v zápisu** explicitně:

```markdown
> **Pozn.:** Část lepíku v Anti-future scénářích nebyla na screenshotu plně čitelná („Prodáváme ___" — méně? jinak?). Doplnit po ověření s klientem.
```

Lepší je explicitní mezera než dohad.

## Když screenshoty chybí, ale ze workshopu byly

Z transkriptu obvykle poznáš, **že facilitátor odkazoval na nástěnku** (*„Já vás přitáhnu k tomuhle lepíku…"*, *„Vidíte tady tu skupinku?"*, *„Pojďte si dát dvě minuty na lepíky."*). Pokud screenshoty nemáš, **doptej se uživatele** — workshop bez nástěnky se zapisuje jen z transkriptu, ale klíčové vizuální struktury budou chybět.
