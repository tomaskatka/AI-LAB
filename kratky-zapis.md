# Krátký zápis z callu nebo schůzky

Výchozí režim pro call a schůzku. Zápis slouží tomu, kdo na callu byl nebo na něj navazuje: co platí, kdo co udělá a co zůstalo otevřené. **Nejvýš jedna strana, zhruba do 500 slov** včetně citací. Slovník, příběhy, hypotézy a atmosféra patří do plného zápisu, sem ne.

> Termíny a data v příkladech v tomto souboru jsou ilustrační (vymyšlené).

## Co si při čtení poznamenat

Z kroku 3 v `SKILL.md` použij body shody a sporu, klíčové citace a otevřené otázky. Navíc si poznamenej:

- **Rozhodnutí** — na čem se účastníci shodli. Ke každému doslovnou citaci, ze které je souhlas vidět. Když souhlas zazněl jen jako „jo“ nebo „ok“, cituj návrh i odpověď.
- **Návrhy** — co někdo navrhl a druhá strana výslovně nepřijala.
- **Úkoly** — kdo, co, do kdy, přesně jak zaznělo.
- **Mezery** — vynechané úseky, chybějící závěr, nesrozumitelná místa, nejisté přiřazení mluvčích.

## Rozhodnutí, úkoly a termíny

Platí i pro follow-up.

- **Rozhodnutí × návrh.** Mezi rozhodnutí patří jen to, na čem se na callu shodli. Návrh bez výslovného souhlasu dej pod „Jen návrh, nerozhodnuto“ nebo mezi otevřené otázky. Když si nejsi jistý, je to návrh.
- **Vlastník a termín** zapiš, jen když zazněly. Jinak do buňky napiš „nezaznělo“. Vlastníka neodvozuj z toho, kdo o věci mluvil.
- **Relativní termín** („do pátku“, „příští týden“) uveď v uvozovkách, jak zazněl, a převod na datum přiznej: *„do tohoto pátku“ (= pá 13. 3., dopočteno z data callu)*. Bez data callu termín nepřeváděj.
- **Nejednoznačný termín** (zazněly dva různé dny, „příští pátek“ může znamenat dva různé týdny) nech u úkolu, jak zazněl, a dej ho i mezi otevřené otázky.
- **Ohlášené téma, které v záznamu chybí,** uveď v mezerách. Rozhodnutí ani úkoly k němu nepiš.

## Šablona

```markdown
# Zápis: {call / schůzka} — {téma} ({D. M. RRRR})

**Kdy:** {den D. M. RRRR, od–do} · **Zdroj:** {strojový přepis / poznámky}
**Účastníci:** {jméno nebo role} ({strana}) · … {když přepis rozlišil jen část mluvčích, napiš to}

## Rozhodnutí

1. **{Co platí, jednou větou.}**
   - {Mluvčí}: „{doslovná citace}“
   - {Mluvčí}: „{doslovný souhlas}“

**Jen návrh, nerozhodnuto:**
- {Návrh} — navrhl {mluvčí}, souhlas nezazněl.

## Úkoly

| Kdo | Co | Do kdy |
|---|---|---|
| {mluvčí, nebo „nezaznělo“} | {úkol} | „{termín, jak zazněl}“ (= {datum}, dopočteno z data callu), nebo „nezaznělo“ |

## Otevřené otázky a neshody

1. **{Otázka nebo neshoda}** — {kdo co řekl, co je potřeba rozhodnout nebo potvrdit}.

## Mezery v záznamu

- {vynechaný úsek / chybějící závěr / nejisté přiřazení mluvčích / co neznáme a nedoplňujeme}
```

Oddíl nevynechávej, ani když je prázdný; napiš do něj „Na callu nezaznělo.“ Když se nevejdeš na stranu, zkrať citace na nejkratší úsek, který nese souhlas, a slučuj drobná rozhodnutí. Oddíly neubírej.

## Hotovo když

- [ ] Zápis se vejde na jednu stranu (zhruba do 500 slov).
- [ ] Má oddíly Rozhodnutí, Úkoly, Otevřené otázky a neshody a Mezery v záznamu.
- [ ] Každá položka má oporu ve vstupu. Každé rozhodnutí má doslovnou citaci, která ve vstupu opravdu stojí. Každou citaci jsi ve vstupu vyhledal a zkopíroval, ne napsal zpaměti.
- [ ] Rozhodnutí je odlišené od návrhu. Spor je mezi otevřenými otázkami.
- [ ] Vlastník ani termín nejsou vymyšlené; kde nezazněly, stojí „nezaznělo“.
- [ ] Relativní termín je uvedený, jak zazněl. Převod na datum je označený jako dopočtený z data callu. Nejednoznačný termín je i mezi otevřenými otázkami.
- [ ] Citace mají mluvčího: jméno, nebo roli z přepisu, když jméno nezaznělo.
- [ ] Mezery v záznamu jsou označené.
