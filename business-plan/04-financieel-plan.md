# 04 — Financieel plan

Laatst bijgewerkt: 2026-06-12

> **Disclaimer:** dit document biedt financiële analyse en scenario's, geen bindend
> fiscaal of juridisch advies. Raadpleeg een boekhouder voor definitieve keuzes over
> statuut (eenmanszaak vs. vennootschap), btw-regime en optimalisatie.

---

## 0. Leeswijzer en openstaande aannames

De `❓`-vragen uit `00-context.md` zijn op dit moment onbeantwoord. De tabel hieronder
toont de aannames die dit plan hanteert zolang Cedric ze niet bevestigt of corrigeert.
**Wijzigt een aanname, dan moeten alle scenario-tabellen herberekend worden.**

| # | Open vraag (uit 00-context.md) | Aanname die dit plan hanteert |
|---|---|---|
| A | Hoeveel uur/week beschikbaar per persoon? | **8 uur/week** per profiel (Jonas + Lien); Cedric coördineert — totaal ~16 uur/week actief. |
| B | Financieel doel bijberoep? | **€ 1.500 netto/maand** als tussentijds doel; **€ 4.000 netto/maand** als drempel voor voltijds. |
| C | Welke prijsrange sprint? | **€ 3.500 – € 6.000 excl. btw** per sprint (wordt onderbouwd in §2). |
| D | Eenmanszaak of vennootschap? | **Eenmanszaak** zolang bijberoep; overweeg BV bij voltijds + winst > € 50.000/jaar. |
| E | Al (proef)klanten of leads? | Geen bekende leads — scenario's starten bij nul. |

> `01-markt.md` en `02-aanbod-opleidingen.md` bestaan nog niet op moment van schrijven.
> Prijsonderbouwing en opleidingsformats zijn gebaseerd op marktonderzoek in dit hoofdstuk
> en worden bijgesteld zodra die hoofdstukken beschikbaar zijn.

---

## 1. Wettelijke kaders (actuele waarden, geraadpleegd 2026-06-12)

### 1.1 Btw-vrijstellingsregeling kleine onderneming

| Parameter | Waarde | Bron |
|---|---|---|
| Drempel 2026 | **€ 25.000** excl. btw per kalenderjaar | [FOD Financiën – vrijstellingsregeling](https://financien.belgium.be/nl/ondernemingen/btw/btw-plicht/vrijstellingsregeling), 2026-06-12 |
| Geplande verhoging (Arizona-wet) | € 30.000 — *nog niet in werking* | [VLAIO](https://www.vlaio.be/nl/nieuws/nieuwe-regeling-btw-vrijstelling-kleine-ondernemingen), 2026-06-12 |
| Overschrijding ≤ 10% | Vrijstelling blijft t/m einde kalenderjaar | [Accountable](https://www.accountable.eu/nl-be/help-center/alles-wat-je-moet-weten-over-de-status-van-btw-vrijstelling-voor-kleine-ondernemingen/), 2026-06-12 |
| Overschrijding > 10% | Btw-plichtig vanaf die transactie | idem |
| Tolerantie (vóór 2025) | Afgeschaft | idem |
| Jaarlijkse omzetmelding | Vóór 31 maart via klantenlisting | [Practicali](https://www.practicali.be/blog/kleine-ondernemingsregeling-nieuwe-omzetmelding-via-de-klantenlisting-uiterlijk-op-31-maart-2026), 2026-06-12 |

**Strategische noot:** zo lang de omzet onder € 25.000 blijft, rekent Auxilia zonder btw —
klant betaalt geen 21% extra en Auxilia hoeft geen kwartaalaangiftes in te dienen. Dit
vereenvoudigt de administratie aanzienlijk in de opstartfase. Bij de grens van ~€ 22.000
omzet is het moment om met de boekhouder te bespreken of vrijwillig btw-plichtig worden
(recht op aftrek van input-btw op tools en materiaal) interessant is.

---

### 1.2 Sociale bijdragen — bijberoep 2026

| Parameter | Waarde | Bron |
|---|---|---|
| Vrijstellingsgrens | **€ 1.922,16** netto belastbaar/jaar | [Liantis – bijberoep](https://www.liantis.be/nl/zelfstandig-worden/sociale-bijdragen/bijberoep), 2026-06-12 |
| Tarief schijf 1 (€ 1.922,16 – € 75.024,54) | **20,50%** van netto belastbaar inkomen | idem |
| Tarief schijf 2 (€ 75.024,54 – € 110.562,42) | **14,16%** | idem |
| Minimumbijdrage (voorlopig, per kwartaal) | **€ 102,40** | idem |
| Drempel waarbij bijdragen = hoofdberoep | **€ 17.374,08**/jaar | [RSVZ / diverse bronnen](https://www.rsvz.be/nl/zelfstandige-bijberoep), 2026-06-12 |
| Bijdragen 100% fiscaal aftrekbaar | Ja | [Accountable](https://www.accountable.eu/nl-be/blog/sociale-bijdragen-zelfstandigen-in-bijberoep/), 2026-06-12 |

**Praktische betekenis:**
- Omzet < € 1.922/jaar → geen sociale bijdragen verschuldigd.
- Omzet € 1.922 – € 17.374/jaar → 20,50% op netto inkomen (= omzet minus kosten).
- Omzet > € 17.374/jaar → bijdragetarief gelijk aan hoofdberoep (minimum € 925,59/kwartaal).
- Bijdragen worden berekend op het werkelijke inkomen van 3 jaar eerder en periodiek
  herberekend — plan altijd een buffer van 20% extra boven je inschatting.

---

### 1.3 Personenbelasting — impact bijberoep

Bijberoepsinkomsten worden opgeteld bij het loon uit het hoofdberoep en belast in de
**hoogste marginale schijf** die de persoon al bereikt.

| Schijf (inkomstenjaar 2026) | Tarief | Bron |
|---|---|---|
| € 0 – € 16.720 | 25% | [Accountable – belastingschijven](https://www.accountable.eu/nl-be/blog/progressieve-belastingschijven/), 2026-06-12 |
| € 16.720 – € 29.510 | 40% | idem |
| € 29.510 – € 51.070 | 45% | idem |
| > € 51.070 | 50% | idem |
| Belastingvrije som 2026 | **€ 10.910** | idem |

**Aanname:** Cedric heeft als loontrekkende een bruto jaarloon dat hem in de 45%- of
50%-schijf plaatst. Bijberoepsinkomsten worden dan belast aan **45–50% marginaal tarief**.
Voeg sociale bijdragen (20,5%) toe → **gecombineerde druk ≈ 55–65%** op de bijdrage
boven de schijfgrens.

> Dit cijfer klinkt zwaar maar is normaal in een Belgische context. De verdediging is:
> - Kosten zijn aftrekbaar (tools, vervoer, boekhouder, verzekering) → verlaag de belastbare basis.
> - Bijdragen zijn zelf ook aftrekbaar.
> - Bij voltijds overstap en BV-structuur daalt de belastingdruk structureel.

---

### 1.4 Kmo-portefeuille (stand: juni 2026)

| Parameter | Waarde | Bron |
|---|---|---|
| Steun kleine onderneming — opleiding | **30%** van de factuurprijs | [VLAIO – hervorming feb 2026](https://www.vlaio.be/nl/nieuws/hervorming-kmo-portefeuille-vanaf-1-februari-2026-enkel-nog-advies-voor-cybersecurity), 2026-06-12 |
| Steun middelgrote onderneming — opleiding | **20%** | idem |
| Verhoogd tarief (digitalisering/cybersecurity) | 45% (klein) / 35% (middel) | idem |
| Maximum steun per bedrijf per jaar | **€ 7.500** | idem |
| Advies subsidieerbaar? | Enkel cybersecurity — overig advies **niet** meer | idem |
| Geldt voor **de sprint**? | **Nee** — de sprint is een implementatietraject/advies, geen erkende opleiding | aanname op basis van definitie |
| DV.O-registratie Auxilia | **Nog niet** aangevraagd | 00-context.md |

**Communicatierichtlijn (zie ook 00-context.md §Subsidies):**
Zolang de DV.O-registratie er niet is, is de kmo-portefeuille **voorwaardelijk**. Auxilia
mag nooit garanderen dat een klant subsidie krijgt. Correcte formulering:
*"Zodra onze erkenning als erkend dienstverlener rond is, kunnen opleidingen in aanmerking
komen voor 30% subsidie via de kmo-portefeuille. We begeleiden je bij de aanvraag."*

**Impact op effectieve prijs voor klant (na DV.O):**

| Catalogusprijs opleiding | Kleine onderneming betaalt (netto) | Middelgrote onderneming betaalt |
|---|---|---|
| € 500 | € 350 | € 400 |
| € 1.000 | € 700 | € 800 |
| € 1.500 | € 1.050 | € 1.200 |
| € 2.500 | € 1.750 | € 2.000 |

---

## 2. Prijszetting

### 2.1 De sprint

**Definitie (uit 00-context.md):** één bedrijfsproces volledig geautomatiseerd en
werkend opgeleverd, vaste prijs, vaste deadline, inclusief opleiding van het team.

**Marktbenchmark (geraadpleegd 2026-06-12):**
- AI-implementatie trajecten voor MKB/KMO (1 proces, 4–8 weken): **€ 5.000 – € 25.000**
  ([Searchlab](https://searchlab.nl/kosten/wat-kost-ai-implementatie), 2026-06-12)
- Freelance AI-consultant dagprijs Nederland/België: **€ 120–€ 300/uur** ≈ **€ 960 – € 2.400/dag**
  ([Consultant.nl/Knab](https://bieb.knab.nl/wat-verdient-een-ai-specialist-zzp-bekijk-uurtarief-en-winst), 2026-06-12)
- Eerste AI-project MKB aanbeveling: **€ 5.000 – € 15.000**
  ([Red Factory / Searchlab](https://redfactory.nl/kennisbank/ai-automatisering/ai-implementatie-kosten/), 2026-06-12)

**Positionering Auxilia:** vaste prijs + garantie ("werkt het niet, dan sturen we bij")
rechtvaardigt een **prijspremie boven uurtariefwerk** maar mag niet de laagdrempeligheid
voor kleine Vlaamse kmo's verliezen.

**Aanname C (zie §0):** € 3.500 – € 6.000 per sprint, excl. btw.

| Variant | Prijs excl. btw | Wanneer |
|---|---|---|
| **Sprint Light** (1 eenvoudig proces, 2–3 weken) | **€ 3.500** | Klant met beperkt budget, duidelijk afgebakend proces |
| **Sprint Standaard** (1 complex proces, 4–5 weken) | **€ 4.750** | Standaard startpunt |
| **Sprint Plus** (meerdere deelprocessen of integraties, 6–8 weken) | **€ 6.000** | Klant die al getest heeft of meer scope vraagt |

**Uurtarief-check:** Sprint Standaard (€ 4.750) bij 60 productieve uren (2 personen × 30 uur
netto) = **€ 79/uur** — conservatief tegenover markt (€ 120–300/uur) en dus haalbaar als
instapprijs voor eerste referentieklanten.

---

### 2.2 Opleidingen

> `02-aanbod-opleidingen.md` bestaat nog niet. Onderstaande prijzen zijn aannames die
> bijgesteld worden zodra de opleidingsontwerper de formats definieert.

**Marktbenchmark:**
- Open dagtraining per deelnemer (Expert Academy BE): **€ 695/persoon/dag** (open)
  ([expertacademy.be](https://www.expertacademy.be/nl/faq/113/hoeveel-kost-een-studiedag-opleiding-of-training), 2026-06-12)
- In-company training België: **€ 1.900 – € 3.000/dag** (forfait)
  (idem)
- AI-workshop basistraining: **€ 150 – € 400/persoon** (halve dag tot volle dag)
  ([VR op Locatie](https://vroplocatie.nl/kennisbank/wat-kost-een-gemiddelde-ai-workshop-per-persoon/), 2026-06-12)
- Freelance trainer dagprijs: **€ 800 – € 1.500/dag**
  (idem)

**Aanname prijsstructuur Auxilia opleidingen:**

| Format | Prijs excl. btw | Toelichting |
|---|---|---|
| Open workshop (halve dag, max. 12 pers.) | **€ 250/deelnemer** | Min. 6 deelnemers = € 1.500 drempel |
| In-company workshop (halve dag, max. 15 pers.) | **€ 1.200 forfait** | Reiskosten inbegrepen tot 50 km |
| In-company workshop (volledige dag, max. 15 pers.) | **€ 1.900 forfait** | idem |
| Opleiding inbegrepen in sprint | **Inbegrepen** | Geen extra factuur; versterkt positionering |

**Subsidie-effect (na DV.O — zie §1.4):** in-company workshop € 1.200 → klant betaalt
netto € 840 (klein) of € 960 (middel). Dit is een sterk verkoopargument zodra de
registratie rond is.

---

## 3. Kostenstructuur bijberoep

### 3.1 Jaarlijkse vaste kosten (aannames)

| Post | Bedrag/jaar (aanname) | Toelichting & bron |
|---|---|---|
| Sociaal secretariaat | € 0 – € 150 | Inbegrepen bij veel fondsen voor bijberoep; bv. Liantis gratis basislidmaatschap. |
| Boekhouder | **€ 600 – € 900** | Eenvoudige boekhouding, eenmanszaak, geen btw-aangifte; ([Xerius – kosten bijberoep](https://www.xerius.be/nl-be/zelfstandig-worden/je-voorbereiding/kosten-in-bijberoep), 2026-06-12; [Accountable – boekhouder](https://www.accountable.eu/nl-be/blog/hoeveel-kost-een-boekhouder/), 2026-06-12). Gebruik **€ 750** als planningsbedrag. |
| Beroepsaansprakelijkheid (BA) | **€ 250 – € 500/jaar** | Voor IT/AI-consultancy; ([hellosafe.be](https://hellosafe.be/nl/beroepsaansprakelijkheidsverzekering/beroepsaansprakelijkheidsverzekering-zelfstandigen), 2026-06-12). Gebruik **€ 350** als planningsbedrag. |
| BA uitbating (optioneel bijberoep) | **€ 100 – € 200/jaar** | Relatief laag risico bijberoep; pas vereist bij grotere klanten. Gebruik **€ 150**. |
| AI-tooling (Claude Pro, ChatGPT, n8n) | **€ 40 – € 80/maand** = **€ 600/jaar** | [Elivado – Claude kosten](https://elivado.nl/claude-ai-kosten/), 2026-06-12 |
| Automatiserings- & productiviteitssoftware | **€ 50 – € 150/maand** = **€ 1.200/jaar** | Make/n8n, Notion, cloud storage |
| Vervoer (klantenbezoeken Kempen/Vlaanderen) | **€ 0,44/km** (fiscaal max.) × ~2.000 km/jaar = **€ 880/jaar** | FOD Financiën km-vergoeding 2026; aanname 2 bezoeken/maand × 80 km gem. |
| Opleidingsmateriaal (handouts, presentaties) | **€ 200/jaar** | Drukwerk, licenties educatieve tools |
| Domein, hosting, website | **€ 100/jaar** | Statische one-pager (index.html in repo) |
| **Totaal vaste kosten/jaar** | **± € 4.230** | Planningsbedrag (middenmoot aannames) |

### 3.2 Variabele kosten per sprint

| Post | Bedrag per sprint |
|---|---|
| Extra cloud/API-gebruik (Gemini, OpenAI) | € 30 – € 100 |
| Reiskosten (gem. 3 bezoeken × 80 km) | € 105 |
| Subcontractor / freelancehulp (indien nodig) | € 0 (aanname: eigen team) |
| **Totaal variabel/sprint** | **± € 175** |

---

## 4. Break-evenanalyse

### 4.1 Aannames break-even

| Parameter | Waarde |
|---|---|
| Gemiddelde sprintprijs | € 4.750 (Sprint Standaard) |
| Variabele kosten per sprint | € 175 |
| Brutomarge per sprint | **€ 4.575** |
| Vaste kosten per jaar | € 4.230 |
| Effectief belastingtarief bijberoepinkomen | 45% (marginaal) + 20,5% sociale bijdragen = ~55% gecombineerd |

### 4.2 Break-even in sprints per jaar

| | Voorzichtig | Verwacht | Optimistisch |
|---|---|---|---|
| Gemiddelde omzet per sprint | € 3.500 | € 4.750 | € 6.000 |
| Vaste kosten + variabele kosten (excl. soc.bijdr./belastingen) | € 4.405 | € 4.405 | € 4.405 |
| **Break-even: sprints/jaar** | **2** (om kosten te dekken) | **1–2** | **1** |
| Netto inkomen bij 4 sprints/jaar | ~€ 9.595 bruto → ~€ 4.318 netto* | ~€ 14.595 bruto → ~€ 6.568 netto* | ~€ 19.595 bruto → ~€ 8.818 netto* |
| Netto inkomen bij 6 sprints/jaar | ~€ 16.595 bruto → ~€ 7.468 netto* | ~€ 24.095 bruto → ~€ 10.843 netto* | ~€ 31.595 bruto → ~€ 14.218 netto* |
| Netto inkomen bij 8 sprints/jaar | ~€ 23.595 bruto → ~€ 10.618 netto* | ~€ 33.595 bruto → ~€ 15.118 netto* | ~€ 43.595 bruto → ~€ 19.618 netto* |

*Netto = bruto omzet − vaste kosten − variabele kosten − sociale bijdragen (20,5%) −
personenbelasting (45% marginaal, na aftrek kosten en sociale bijdragen). Dit is een
conservatieve benadering; werkelijke netto kan hoger zijn via meer kostenaftrek.*

> **Aanname B revisited:** om € 1.500/maand netto = € 18.000/jaar netto te bereiken,
> heb je bij de *verwachte* prijzen en 45% belastingdruk een **bruto-inkomen van ± € 40.000**
> nodig — d.w.z. kosten (€ 4.230) + sociale bijdragen (~€ 7.380) + belasting (~€ 8.370)
> + netto (€ 18.000) → **± 8–9 sprints/jaar (verwacht scenario).**

---

## 5. Drie omzetscenario's — jaar 1 t/m jaar 3

### Scenario-aannames

| Parameter | Voorzichtig | Verwacht | Optimistisch |
|---|---|---|---|
| Sprints/kwartaal | 1 | 2 | 3 |
| Sprints/jaar | **4** | **8** | **12** |
| Gem. sprintprijs | € 3.500 | € 4.750 | € 5.500 |
| Opleidingen/jaar (in-company, forfait €1.200) | 2 | 6 | 10 |
| Open workshops/jaar (gem. € 1.500 = 6 pers. × €250) | 0 | 2 | 4 |
| Totale omzet/jaar | **€ 16.400** | **€ 52.600** | **€ 88.000** |
| Btw-regime | Vrijgesteld | **Btw-plichtig vanaf € 25.000** | Btw-plichtig |

> *Voorzichtig*: net boven btw-drempel maar dicht genoeg voor vrijstelling bij start.
> *Verwacht + optimistisch*: btw-plicht treedt in; prijzen zijn sowieso excl. btw.

### 5.1 Scenario Voorzichtig — jaar 1

| Post | Bedrag |
|---|---|
| Omzet (4 sprints × €3.500 + 2 opl. × €1.200) | **€ 16.400** |
| − Vaste kosten | − € 4.230 |
| − Variabele kosten (4 × €175) | − € 700 |
| **= Netto belastbaar inkomen** | **€ 11.470** |
| − Sociale bijdragen (20,5% × €11.470) | − € 2.351 |
| **= Fiscaal inkomen** | **€ 9.119** |
| − Personenbelasting (45%, na aftrek soc.bijdr. als kost) | − € 3.408 |
| **= Netto beschikbaar** | **≈ € 5.711/jaar** ≈ **€ 476/maand** |
| Btw-regime | Vrijgesteld (< €25.000) |
| Sprints/kwartaal | 1 |

### 5.2 Scenario Verwacht — jaar 2

| Post | Bedrag |
|---|---|
| Omzet (8 sprints × €4.750 + 6 opl. × €1.200 + 2 open workshops × €1.500) | **€ 48.200** |
| − Vaste kosten (inclusief btw-aangifte boekhouder ↑ €250) | − € 4.480 |
| − Variabele kosten (8 × €175) | − € 1.400 |
| **= Netto belastbaar inkomen** | **€ 42.320** |
| − Sociale bijdragen (20,5% × €42.320) | − € 8.676 |
| **= Fiscaal inkomen** | **€ 33.644** |
| − Personenbelasting (25%/40%/45% progressief, excl. belastingvrije som) | − € 11.800 (schatting) |
| **= Netto beschikbaar** | **≈ € 21.844/jaar** ≈ **€ 1.820/maand** |
| Btw-regime | Btw-plichtig (> €25.000) — 21% bovenop factuurprijs |

> Doel B (€ 1.500 netto/maand) **bereikt** in verwacht scenario jaar 2.

### 5.3 Scenario Optimistisch — jaar 3

| Post | Bedrag |
|---|---|
| Omzet (12 sprints × €5.500 + 10 opl. × €1.200 + 4 open workshops × €1.500) | **€ 84.000** |
| − Vaste kosten | − € 4.480 |
| − Variabele kosten (12 × €175) | − € 2.100 |
| **= Netto belastbaar inkomen** | **€ 77.420** |
| − Sociale bijdragen (20,5% t/m €75.024 + 14,16% op rest) | − € 15.745 |
| **= Fiscaal inkomen** | **€ 61.675** |
| − Personenbelasting (progressief + gemeentebelasting) | − € 25.100 (schatting) |
| **= Netto beschikbaar** | **≈ € 36.575/jaar** ≈ **€ 3.048/maand** |
| Btw-regime | Btw-plichtig |

> Bij het optimistisch scenario nadert men de drempel voor voltijds (aanname B: €4.000/maand
> netto). Tweekoppig team: per persoon ~€ 1.524/maand — nog net niet het voltijds-signaal
> als inkomen gedeeld wordt.

---

## 6. Drempels en beslismomenten

### 6.1 Btw-drempel — actie vereist

| Drempel | Actie |
|---|---|
| Omzet bereikt **€ 22.000** | Gesprek met boekhouder: vrijwillig btw-plichtig worden? (input-aftrek vs. administratie) |
| Omzet bereikt **€ 25.000** | Btw-plichtig worden vanaf volgende transactie boven drempel (tenzij ≤ 10% overschrijding binnen hetzelfde jaar) |
| Omzet > **€ 27.500** (> 10% over drempel) | Onmiddellijk btw-plichtig vanaf die transactie |

### 6.2 Sociale bijdragen — drempels bijberoep 2026

| Drempel netto inkomen/jaar | Gevolg |
|---|---|
| < € 1.922 | Geen sociale bijdragen |
| € 1.922 – € 17.374 | 20,5% op netto inkomen; **geen** minimumbijdrage hoofdberoep |
| ≥ € 17.374 | Zelfde tarief als hoofdberoep; minimumbijdrage **€ 925,59/kwartaal** geldt |
| ≥ € 75.024 | Bovenste schijf: 14,16% |

**Praktisch:** bij een netto inkomen van € 17.374 springen de sociale bijdragen van
~€ 3.562/jaar naar minimum **€ 3.702/jaar** (4 × €925,59). Het verschil is beperkt,
maar het is een momentopname om te kennen.

### 6.3 Wanneer voltijds?

**Financiële drempel (bijgesteld op aanname B: € 4.000 netto/maand):**

Om € 4.000/maand = € 48.000/jaar netto te halen als **zelfstandige in hoofdberoep**
(na sociale bijdragen ~22% en belasting ~40–45% na aftrekken), heb je een **bruto omzet
van ± € 110.000 – € 130.000** nodig.

Als **bijberoeper** zijn de sociale bijdragen lager en val je terug op de sociale
bescherming van het hoofdberoep — voltijds overstappen is dus ook een
**levenskwaliteitsbeslissing** (werkzekerheid, verlof, ziekte) los van de cijfers.

**Checklist voor voltijds:**

| Criterium | Drempelwaarde |
|---|---|
| Aantoonbare omzet laatste 12 maanden | ≥ € 60.000 excl. btw |
| Bevestigde pipeline (getekende offertes) | ≥ € 30.000 |
| Reservebuffer opgebouwd | ≥ 6 maanden persoonlijke vaste lasten |
| Aantal vaste klanten | ≥ 3 terugkerende relaties |
| Sociale bijdragen hoofdberoep ingeschat en afgedekt | Ja |

**Wat verandert bij voltijds:**
- Sociale bijdragen: minimum **€ 925,59/kwartaal** (= € 3.702/jaar), ongeacht inkomen
- Verzekering gewaarborgd inkomen wordt aanbevolen: premie **€ 40 – € 130/maand** afhankelijk
  van leeftijd en gedekte bedrag ([Acerta – gewaarborgd inkomen](https://www.acerta.be/nl/inspiratie/verzekering-gewaarborgd-inkomen-prijs), 2026-06-12)
- Recht op arbeidsongeschiktheidsuitkering via RIZIV (zelfstandigenregeling) — maar dit is
  veel lager dan de wettelijke werknemer-uitkering → gewaarborgd inkomen is essentieel
- Vennootschapsstructuur (BV) overwegen bij winst > ~€ 50.000/jaar: vennootschapsbelasting
  25% (of verlaagd tarief 20% op eerste € 100.000 voor kleine vennootschappen) vs.
  personenbelasting 45–50%

---

## 7. Kmo-portefeuille — impact op commerciële strategie

### 7.1 De sprint is **niet** subsidieerbaar (nu noch na DV.O)

De kmo-portefeuille dekt **opleiding**, niet implementatie/advies (behalve cybersecurity
advies). Een sprint is primair een implementatietraject. Enkel als de sprint een
aantoonbaar opleidingscomponent bevat die los gefactureerd wordt, kan dat deelluik
subsidieerbaar zijn.

**Aanbeveling:** splits de factuur van een Sprint Standaard (€ 4.750) in:
- Implementatie + begeleiding: € 3.500 (niet subsidieerbaar)
- Teamopleiding: € 1.250 (subsidieerbaar na DV.O; kleine onderneming betaalt netto € 875)

Zo daalt de netto klantprijs voor het opleidingsluik van € 1.250 naar € 875 — een
**verkoopargument van € 375 subsidie zonder de implementatieprijs te verlagen.**

### 7.2 Maximaal subsidiebedrag

Klant kan max. € 7.500 subsidie per jaar ontvangen. Bij een catalogusopleiding van
€ 2.500/dag (in-company, 2 sessies) recupereert de kleine klant € 1.500 — duidelijk
communiceerbaar.

> Herhaling: dit alles is pas geldig **na afronding DV.O-registratie**. Zolang die er
> niet is, spreekt Auxilia altijd in de toekomende tijd.

---

## 8. Cashflowplanning jaar 1

### 8.1 Betalingsgedrag kmo's en aanbevolen betalingsstructuur

| Fase | Aanpak |
|---|---|
| Offerte getekend | **30–40% voorschot** (Auxilia start pas na ontvangst) |
| Halverwege sprint (oplevering tussentijds) | **30% tweede schijf** |
| Eindoplevering | **30–40% saldo** binnen 30 dagen |
| Betalingstermijn | Max. **30 dagen** (Wet Betalingstermijnen B2B, max. 60 d. tenzij uitdrukkelijk overeengekomen) |

**Praktisch:** bij sprint van € 4.750 incasseert Auxilia:
- Start: € 1.425 (30%)
- Week 3: € 1.425 (30%)
- Einde: € 1.900 (40%) → binnen 30 d. na oplevering

Dit beschermt tegen wanbetaling en financiert de lopende kosten.

### 8.2 Kwartaalcashflow jaar 1 (verwacht scenario: 2 sprints/kwartaal)

| Kwartaal | Omzet (incasso) | Vaste kosten | Sociale bijdragen (voorlopig) | Netto cashflow |
|---|---|---|---|---|
| Q1 (jan–mrt) | € 9.500 | € 1.057 | € 409 | **€ 8.034** |
| Q2 (apr–jun) | € 9.500 | € 1.057 | € 409 | **€ 8.034** |
| Q3 (jul–sep) | € 9.500 | € 1.057 | € 409 | **€ 8.034** |
| Q4 (okt–dec) | € 9.500 | € 1.057 | € 409 | **€ 8.034** |
| **Jaar 1 totaal** | **€ 38.000** | **€ 4.230** | **€ 1.636** | **€ 32.134** |
| **Belastingprovision (45%)** | | | | **− € 14.460** |
| **Netto beschikbaar** | | | | **≈ € 17.674** ≈ **€ 1.473/maand** |

> **Let op:** btw-herberekening sociale bijdragen 2 jaar later. Plan een aparte buffer
> van **€ 200 – € 300/maand** voor de definitieve bijdrageafrekening.
>
> **Btw:** bij het verwachte scenario passeert de omzet de € 25.000-drempel in Q2/Q3
> jaar 1. Zodra die drempel gepasseerd is: btw aanrekenen op nieuwe facturen, kwartaal-
> aangifte indienen. Gesprek met boekhouder plannen in Q1 over optimale timing.

---

## 9. Samenvatting kerncijfers

| Indicator | Voorzichtig | Verwacht | Optimistisch |
|---|---|---|---|
| Jaaromzet | € 16.400 | € 48.200 | € 84.000 |
| Netto beschikbaar | ≈ € 5.700 | ≈ € 21.800 | ≈ € 36.600 |
| Netto/maand | ≈ € 476 | ≈ € 1.820 | ≈ € 3.048 |
| Sprints/jaar | 4 | 8 | 12 |
| Btw-regime | Vrijgesteld | Plichtig (> €25.000) | Plichtig |
| Break-even (kosten) | 2 sprints | 1–2 sprints | 1 sprint |
| Doel A bereikt (€1.500/mnd)? | **Nee** | **Ja (€ 1.820)** | Ruim ja |
| Doel B bereikt (€4.000/mnd voltijds)? | Nee | Nee (€ 1.820) | **Nadert (€ 3.048)** |

---

## 10. Bronnenlijst

| Bron | URL | Geraadpleegd |
|---|---|---|
| Liantis — sociale bijdragen bijberoep | https://www.liantis.be/nl/zelfstandig-worden/sociale-bijdragen/bijberoep | 2026-06-12 |
| Accountable — sociale bijdragen bijberoep | https://www.accountable.eu/nl-be/blog/sociale-bijdragen-zelfstandigen-in-bijberoep/ | 2026-06-12 |
| Accountable — belastingschijven 2026 | https://www.accountable.eu/nl-be/blog/progressieve-belastingschijven/ | 2026-06-12 |
| Accountable — fiscale wijzigingen 2026 | https://www.accountable.eu/nl-be/blog/fiscale-wijzigingen/ | 2026-06-12 |
| FOD Financiën — btw-vrijstellingsregeling | https://financien.belgium.be/nl/ondernemingen/btw/btw-plicht/vrijstellingsregeling | 2026-06-12 |
| VLAIO — nieuwe btw-vrijstelling kleine ondernemingen | https://www.vlaio.be/nl/nieuws/nieuwe-regeling-btw-vrijstelling-kleine-ondernemingen | 2026-06-12 |
| VLAIO — hervorming kmo-portefeuille feb 2026 | https://www.vlaio.be/nl/nieuws/hervorming-kmo-portefeuille-vanaf-1-februari-2026-enkel-nog-advies-voor-cybersecurity | 2026-06-12 |
| RSVZ — zelfstandige bijberoep | https://www.rsvz.be/nl/zelfstandige-bijberoep | 2026-06-12 |
| Xerius — kosten bijberoep | https://www.xerius.be/nl-be/zelfstandig-worden/je-voorbereiding/kosten-in-bijberoep | 2026-06-12 |
| Accountable — boekhouder kosten | https://www.accountable.eu/nl-be/blog/hoeveel-kost-een-boekhouder/ | 2026-06-12 |
| hellosafe.be — beroepsaansprakelijkheid | https://hellosafe.be/nl/beroepsaansprakelijkheidsverzekering/beroepsaansprakelijkheidsverzekering-zelfstandigen | 2026-06-12 |
| Searchlab — AI implementatie kosten | https://searchlab.nl/kosten/wat-kost-ai-implementatie | 2026-06-12 |
| Expert Academy — prijs studiedag | https://www.expertacademy.be/nl/faq/113/hoeveel-kost-een-studiedag-opleiding-of-training | 2026-06-12 |
| VR op Locatie — AI workshop prijs | https://vroplocatie.nl/kennisbank/wat-kost-een-gemiddelde-ai-workshop-per-persoon/ | 2026-06-12 |
| Elivado — Claude AI kosten | https://elivado.nl/claude-ai-kosten/ | 2026-06-12 |
| Acerta — verzekering gewaarborgd inkomen | https://www.acerta.be/nl/inspiratie/verzekering-gewaarborgd-inkomen-prijs | 2026-06-12 |
| Practicali — kleine ondernemingsregeling omzetmelding | https://www.practicali.be/blog/kleine-ondernemingsregeling-nieuwe-omzetmelding-via-de-klantenlisting-uiterlijk-op-31-maart-2026 | 2026-06-12 |
