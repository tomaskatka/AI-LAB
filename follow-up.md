# Follow-up pro účastníky

Návrh zprávy, kterou uživatel po callu, schůzce nebo workshopu pošle účastníkům: na čem se domluvili, kdo co udělá do kdy a co je potřeba potvrdit. **Je to návrh. Nic neodesíláš.**

> Termíny a data v příkladech v tomto souboru jsou ilustrační (vymyšlené).

## Než začneš

- Rozhodnutí, úkoly a termíny ber podle oddílu „Rozhodnutí, úkoly a termíny“ v `kratky-zapis.md`. Když krátký zápis z téhož callu už ve `vystupy/` je, vyjdi z něj.
- **Za koho a komu.** Piš za uživatele, účastníkům druhé strany. Když ze vstupu ani zadání nepoznáš, na které straně uživatel byl, komu zpráva jde a jestli si tykají, zeptej se jednou otázkou s možnostmi. Co zůstane neznámé, nech v textu jako [značku] v hranatých závorkách.

## Šablona

```markdown
# Follow-up: {téma} ({D. M. RRRR})

> Návrh k odeslání. Neodesláno — odešle uživatel po kontrole.

**Komu:** {účastníci, nebo [doplnit]}
**Předmět:** {téma}: shrnutí a další kroky ({D. M.})

{[Oslovení]},

díky za {dnešní / úterní} call. Posílám krátké shrnutí.

**Na čem jsme se domluvili**
- {rozhodnutí jednou větou}

**Další kroky**
- {Kdo}: {co} — {termín, jak zazněl, s datem v závorce}

**Otevřené a k potvrzení**
- {spor, nejednoznačný termín nebo otázka, kterou má adresát rozhodnout}

{Závěr jednou větou.}
{[Podpis]}

---

## Pro kontrolu (neodesílat)

| Ve zprávě | Opora ve vstupu (doslova) |
|---|---|
| {rozhodnutí / úkol} | {Mluvčí}: „{citace}“ |

- **Dopočtené termíny:** „{jak zazněl}“ = {datum}, dopočteno z data callu {D. M. RRRR}.
- **Co ve zprávě není a proč:** {návrhy bez souhlasu, interní poznámky, mezery v záznamu}.
- **[Značky] k doplnění:** {seznam}.
```

## Jak psát

- Text k odeslání má **zhruba do 200 slov**. Krátké věty, věcně, bez hodnocení průběhu.
- Do zprávy patří rozhodnutí, další kroky a otevřené body. Spor, nejednoznačný termín a návrh bez souhlasu dej pod „Otevřené a k potvrzení“, ne mezi domluvené.
- Termín piš srozumitelně pro adresáta: jak zazněl a datum v závorce, *„do tohoto pátku (13. 3.)“*. Převod přiznej v části Pro kontrolu.
- Téma, které na callu bylo, ale v záznamu chybí, uveď ve zprávě jako *[doplnit: {téma} — v záznamu chybí]*, ať ho uživatel dopíše, nebo smaže.
- Citace do textu zprávy nedávej. Patří do části Pro kontrolu, ať jde každou větu zprávy ověřit.
- Uvozovky jen pro doslovné znění. Termín i citaci zkopíruj ze vstupu přesně, zkrácení označ „…“. Parafrázi piš bez uvozovek.
- Pojmy (skupiny zákazníků, názvy stránek a produktů, role) piš slovy ze vstupu, jak zazněly, i když je to delší.

## Hotovo když

- [ ] Návrh je uložený ve `vystupy/` a nic se neodeslalo.
- [ ] Text k odeslání má shrnutí, další kroky a otevřené body a vejde se zhruba do 200 slov.
- [ ] Každé rozhodnutí a úkol ve zprávě má v části Pro kontrolu doslovnou citaci, která ve vstupu opravdu stojí. Každou citaci jsi ve vstupu vyhledal a zkopíroval, ne napsal zpaměti.
- [ ] Vlastník ani termín nejsou vymyšlené. Dopočtené datum je přiznané. Nejednoznačný termín je mezi otevřenými body.
- [ ] Návrh bez souhlasu ani spor nejsou ve zprávě podané jako dohoda.
- [ ] Mezery v záznamu jsou v části Pro kontrolu, chybějící téma je ve zprávě jako [doplnit].
- [ ] Neznámé údaje (adresát, oslovení, podpis) jsou [značky], ne odhad.
