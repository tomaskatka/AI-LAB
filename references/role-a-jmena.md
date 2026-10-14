# Role a jména

Klientský workshop ≠ trénink. Účastníci se **uvádějí jmenovitě s rolemi**, ne anonymizovaně. Tyto role pak slouží:

- **Jako kontext pro citace** — kdo z jaké pozice mluví („Petr Novák, obchodní ředitel: …" má jinou váhu než „Petr z marketingu: …")
- **Jako disambiguace** — pokud jsou duplicitní jména (stejné jméno, různí lidé)
- **Jako orientace pro budoucí čtenáře projektu** — sense-making, strategie, IA mohou vznikat měsíce po workshopu

> Jména, role a citace v příkladech v tomto souboru jsou ilustrační (vymyšlené).

## Kdo se jmenuje jmenovitě

| Kdo | Jak v zápisu |
|---|---|
| **Facilitátoři HoŘ** | Jmenovitě (jméno + příjmení v frontmatteru, dál křestní). |
| **Účastníci klienta** | **Jmenovitě s rolí**. „Petr Novák (obchodní ředitel)", dál „Petr ([Klient])" nebo dle disambiguace. |
| **Externí osoby zmíněné v debatě** | Jmenovitě (dodavatelé, konkurenti, výrobci značek, zákazníci). |
| **Konkrétní zákazníci klienta** (anekdoty) | Pokud je klient explicitně jmenuje (jménem a povoláním, jak zazněly v anekdotě), uveď tak, jak je klient zmínil. |

## Kdo se anonymizuje (i v klientském workshopu)

V zásadě **nikdo**. Workshop zápis je **interní pracovní materiál** projektu — nesdílí se mimo HoŘ tým a klienta. Není potřeba anonymizovat.

**Výjimka:** pokud klient explicitně řekne „toto se nesmí dostat ven" o konkrétním zákazníkovi nebo dodavateli, respektuj to a anonymizuj v zápisu (*„zákazník z bankovnictví"*, *„konkurenční dealer v regionu"*).

## Disambiguace duplicitních jmen

Typický případ: **facilitátor a člověk z klienta se stejným křestním jménem** sedí na stejném workshopu. Nebo i 2 lidé stejného jména na straně klienta (např. 3× Petr — obchodní ředitel, vedoucí servisu, plus facilitátor).

### Postup pro disambiguaci

**Ve frontmatteru:**

```yaml
účastníci klient: Petr Novák (obchodní ředitel — jiný Petr než facilitátor) · Petr Svoboda (vedoucí servisu) · ...
```

**Pod frontmatterem nebo v sekci „Kontext":**

```markdown
> Pozor: na workshopu byli 3× Petr — Petr Novák (klient, obchodní ředitel) · Petr Svoboda (klient, vedoucí servisu) · Petr Dvořák (facilitátor). Všechny zmínky *„Petr z {klient}"* / *„Petr ([Klient])"* v textu = Petr Novák (klient, obchodní ředitel).
```

**V textu pak používej krátké identifikátory:**

- *„Petr ([Klient])"* nebo *„Petr z [Klient]"* = klient (nejčastější mluvčí)
- *„Petr Svoboda"* (plné jméno, abychom ho rozlišili)
- *„Petr (facilitátor)"* nebo prostě *„facilitátor"* = facilitátor

## Pokud nemáš plná jména účastníků

V transkriptu typicky figurují jen **křestní jména** (jak se účastníci vzájemně oslovují). Pro plný zápis potřebuješ:

1. **E-mail nebo dokument od klienta s anotací workshopu** — typicky organizátor (např. kontaktní osoba u klienta) posílá seznam účastníků s rolemi předem nebo po.
2. **Pokud nemáš tento dokument, doptej se uživatele.** Bez plných jmen a rolí nelze udělat kvalitní zápis — riskuješ:
   - Záměnu osob (3× stejné křestní jméno)
   - Špatnou atribuci citací
   - Ztrátu kontextu role (vedoucí divize vs. obchodník mají jiný hlas v debatě)

**Workflow:** v draft v1 můžeš použít křestní jména s placeholdery a flagnout v patičce *„doplnit plná jména a role"*. Pak v v2 (po dodání kontextu od klienta) doplň.

## Jak používat role v textu

### Tabulka rolí v sekci „Kontext"

```markdown
| Osoba | Role | Co přináší do debaty |
|---|---|---|
| **Petr Novák** | Obchodní ředitel | Celkový pohled na obchod a servis, klíčový pohled na to, proč odcházejí stálí zákazníci. |
| **Eva Horáková** | Vedoucí zákaznické podpory | Nejblíž zákazníkům, zná nejčastější dotazy a stížnosti. |
| ...
```

### Atribuce citací

```markdown
Petr Novák ([Klient]) opakovaně argumentoval pro rychlost před úplností: *„Radši budu mít web za tři měsíce s polovinou obsahu než za rok kompletní."*
```

### Identifikace mluvčího při sporu

Pokud byla v workshopu debata mezi dvěma účastníky, **uveď oba jmenovitě** a popiš jejich pozice:

```markdown
**Eva** (zákaznická podpora) zahájila otázku: *„Chtějí zákazníci mluvit s člověkem, nebo jim stačí najít odpověď sami?"* **Karel Veselý** (produktový manažer) kontroval: *„Většina dotazů je pořád stejná — kdyby to bylo na webu, nevolali by."* **Petr Novák ([Klient])** souhlasil s Karlem.
```

## Uložení pro další práci

Při vytvoření zápisu, kde jsou **účastníci s rolemi**, **doplň je do `wiki/`** (stránka o klientovi a jeho týmu) a odkaz na ni zapiš do `index.md`. `CLAUDE.md` ani jiný soubor s instrukcemi nezakládej. Tím zajistíš, že v dalších konverzacích o projektu nedojde k záměně.

Speciálně **disambiguaci duplicitních jmen** zapiš do té stránky ve `wiki/` **explicitně** — je to typ kontextu, který se snadno ztratí.
