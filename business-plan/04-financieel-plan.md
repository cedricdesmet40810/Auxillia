# 04 — Financieel plan

Laatst bijgewerkt: 2026-06-12 (rev. 2 — AI-analyse als kernproduct, DV.O-audit uit near-term kosten, T-2/T-3 correcties)

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
| F | Definitieve prijs AI-analyse? | **€ 750** (marktbenchmark uit `01-markt.md` — AI voor KMO AI-scan); Cedric beslist de definitieve prijs. |
| G | Conversieratio analyse → sprint? | **40%** (aanname): 4 op 10 klanten die een AI-analyse kopen, boeken daarna een sprint. |

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
| Geldt voor **de AI-analyse**? | **Nee** — het is een adviestraject, geen opleiding | idem |
| DV.O-registratie Auxilia | **Niet aangevraagd; voorlopig uitgesteld** | 00-context.md beslissing 2026-06-12 |

**Communicatierichtlijn (zie ook 00-context.md §Subsidies):**
Zolang de DV.O-registratie er niet is, is de kmo-portefeuille **voorwaardelijk**. Auxilia
mag nooit garanderen dat een klant subsidie krijgt. Correcte formulering:
*"Zodra onze erkenning als erkend dienstverlener rond is, kunnen opleidingen in aanmerking
komen voor 30% subsidie via de kmo-portefeuille. We begeleiden je bij de aanvraag."*

**Geen subsidie-effect in de scenario's van dit plan:**
De DV.O-registratie is uitgesteld (beslissing 2026-06-12). Alle scenario's rekenen met
brutoprijzen **zonder subsidie-effect**. Dit is de correcte conservatieve aanname: de
vraag naar opleidingen wordt niet opgedreven door een kortingsprikkel die Auxilia op
korte termijn niet kan bieden. Wanneer de registratie wél rond is, verbetert de
effectieve prijs voor de klant maar stijgen de opbrengsten voor Auxilia zelf niet —
het subsidie-effect is een verkoopargument, geen extra omzet voor Auxilia.

---

## 2. Prijszetting

### 2.1 De AI-analyse (instapproduct) — nieuw kernproduct

**Definitie (uit 00-context.md, beslissing 2026-06-12):** betaalde doorlichting van de
processen van de kmo met een concreet rapport: waar zit de winst, wat is haalbaar, wat zou
het kosten. Eindigt altijd in een voorstel voor een sprint (optioneel vervolg).

**Marktbenchmark:**
- AI voor KMO AI-scan (halve dag + rapport binnen 5 werkdagen): **€ 750**
  ([aivoorkmo.be](https://aivoorkmo.be/), geraadpleegd 2026-06-12)
- Gemiddeld dagtarief AI-consultant België: **€ 700–€ 1.100/dag**
  ([algida.be/freelance-tarieven-2025](https://algida.be/freelance-tarieven-2025/), 2026-06-12)

**Aanname F:** definitieve prijs **€ 750** excl. btw. ❓ Cedric beslist definitieve prijs
(range: € 650–€ 950 — lager dan marktleider is mogelijk als lanceringsstrategie, hoger
als het rapport meer diepgang biedt dan de benchmark).

| Wat is inbegrepen | Tijdsinvestering |
|---|---|
| Intake-gesprek ter plaatse of online (1–1,5 uur) | ~1,5 uur |
| Analyse van 2–3 bedrijfsprocessen | ~2 uur voorbereiding |
| Schriftelijk rapport met prioriteitenlijst + indicatieve kostenraming | ~1,5 uur |
| Presentatie rapport (30 min online of ter plaatse) | ~0,5 uur |
| **Totaal per analyse** | **~5,5 uur** |

**Uurtarief-check:** € 750 bij 5,5 uur = **€ 136/uur** — bovenaan de marktrange (€ 60–
€ 150/uur) voor een junior AI-profiel, en goed verdedigbaar gezien het concrete rapport.

**Rol in de funnel:**
- De AI-analyse genereert cashflow vóór de sprint begint.
- Ze kwalificeert de klant: Auxilia investeert pas in een sprint bij een klant die al
  betaald heeft voor het vooronderzoek en het rapport kent.
- Aanname G (conversieratio): **40%** van de analyses leidt tot een sprint. Dit is een
  kritische aanname — zie §5.

**Cashflowtiming:** de analyse wordt volledig vooraf gefactureerd (€ 750 bij ondertekening
van de offerte) of 50% bij start / 50% bij oplevering rapport. Geen betalingstermijnrisico.

---

### 2.2 De sprint

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

**Link met AI-analyse:** een klant die eerst een analyse kocht (€ 750), betaalt bij een
Sprint Standaard de totale funnel-waarde: **€ 750 + € 4.750 = € 5.500**. Dit is volledig
in lijn met de marktbenchmark voor een bewuste, voorbereide kmo.

---

### 2.3 Opleidingen

> **Actualisering t.o.v. rev. 1:** `02-aanbod-opleidingen.md` (rev. 2, 2026-06-12) bestaat
> nu en bevat concrete prijsranges. De prijzen hieronder zijn bijgesteld op basis van die
> gegevens. **Aandachtspunt T-2:** de vorige versie van dit hoofdstuk hanteerde € 250/
> deelnemer voor een open workshop (halve dag). Hoofdstuk 02 specificeert echter een
> volledige dagcursus aan **€ 395–€ 450 p.p.** voor de open workshop. De scenario-aannames
> worden hieronder gecorrigeerd. Er is geen halve-dag open format in het definitieve aanbod
> — dat label is komen te vervallen.

**Prijsstructuur Auxilia opleidingen (gebaseerd op `02-aanbod-opleidingen.md` §2.1):**

| Format | Prijs excl. btw | Toelichting |
|---|---|---|
| Open workshop (1 dag, max. 12 pers.) | **€ 395–€ 450/deelnemer** | Uit `02-aanbod-opleidingen.md` §2.1; scenarioplanning gebruikt **€ 420** als middenpunt. Min. 8 deelnemers = € 3.360 drempel bij € 420/p.p. |
| Verdiepingsmodule (halve dag, open, max. 12 pers.) | **€ 295–€ 345/deelnemer** | Uit `02-aanbod-opleidingen.md` §4.4; scenarioplanning gebruikt **€ 320** als middenpunt. |
| In-company workshop (1 dag, max. 15 pers.) | **€ 1.800–€ 2.400 forfait** | Uit `02-aanbod-opleidingen.md` §2.1; scenarioplanning gebruikt **€ 2.000** als middenpunt. |
| In-company workshop (halve dag, max. 15 pers.) | **€ 900–€ 1.200 forfait** | Schatting (helft dagprijs); scenarioplanning gebruikt **€ 1.050** als middenpunt. |
| Abonnement doorlopend (online, per bedrijf/maand) | **€ 149–€ 199/maand** | Uit `02-aanbod-opleidingen.md` §2.1; pas actief in jaar 2+. |
| Opleiding inbegrepen in sprint | **Inbegrepen** | Geen extra factuur; versterkt positionering |

**Noot subsidieaannames:** de scenario-omzet voor opleidingen wordt berekend **zonder**
subsidie-effect (DV.O uitgesteld — zie §1.4). Klanten betalen de volle prijs. Zodra
de registratie rond is, verandert de netto klantprijs maar niet de Auxilia-omzet.

**Marktconformiteitscheck:**
- AI Learning open sessie (1 dag): € 425/deelnemer — Auxilia zit met € 395–450 goed in lijn.
- Syntra AI-agents (6u, 2 sessies): € 395/deelnemer — Auxilia ligt gelijk.
- Voka "basics" (halve dag): € 255–385 — Auxilia is licht hoger maar biedt een volle dag.

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
| DV.O-auditkosten | **€ 0 (near-term)** | Beslissing 2026-06-12: registratie uitgesteld. Audit kost € 800–€ 2.500 (Bureau Veritas, DNV, BQA) — heroverwegen zodra opleidingen aantoonbaar verkopen. Niet in de near-term kostenstructuur opgenomen. |
| **Totaal vaste kosten/jaar** | **± € 4.230** | Planningsbedrag (middenmoot aannames; exclusief DV.O-audit) |

> **T.o.v. rev. 1:** de DV.O-auditpost (€ 800–€ 2.500) is verwijderd uit de actieve
> kostentabel op basis van de beslissing van 2026-06-12. Ze blijft vermeld als toekomstige
> investering wanneer de registratie heropgestart wordt.

### 3.2 Variabele kosten per sprint

| Post | Bedrag per sprint |
|---|---|
| Extra cloud/API-gebruik (Gemini, OpenAI) | € 30 – € 100 |
| Reiskosten (gem. 3 bezoeken × 80 km) | € 105 |
| Subcontractor / freelancehulp (indien nodig) | € 0 (aanname: eigen team) |
| **Totaal variabel/sprint** | **± € 175** |

### 3.3 Variabele kosten per AI-analyse

| Post | Bedrag per analyse |
|---|---|
| Reiskosten (1 bezoek × 80 km) | € 35 |
| Rapportage-tools, AI-gebruik voor analyse | € 15 |
| **Totaal variabel/analyse** | **± € 50** |

---

## 4. Break-evenanalyse

### 4.1 Aannames break-even

| Parameter | Waarde |
|---|---|
| Gemiddelde sprintprijs | € 4.750 (Sprint Standaard) |
| Variabele kosten per sprint | € 175 |
| Brutomarge per sprint | **€ 4.575** |
| Gemiddelde prijs AI-analyse | € 750 |
| Variabele kosten per analyse | € 50 |
| Brutomarge per AI-analyse | **€ 700** |
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
> + netto (€ 18.000) → **± 8–9 sprints/jaar (verwacht scenario).** De AI-analyses helpen
> dit gat dichten door cashflow te genereren in de wachtperiode tussen sprints.

---

## 5. Drie omzetscenario's — jaar 1 t/m jaar 3

### Scenario-aannames

> **Correctie T-3 (rev. 2):** de vorige parametertabel vermeldde **€ 52.600** als verwacht
> scenario, terwijl de detailberekening in §5.2 uitkwam op **€ 48.200**. De detailberekening
> was juist (8 × € 4.750 + 6 × € 1.200 + 2 × € 1.500 = € 38.000 + € 7.200 + € 3.000 =
> € 48.200). De parametertabel bevatte een rekenfout. Beide zijn nu gecorrigeerd naar het
> herziene verwacht scenario — zie de nieuwe tabel.
>
> **Correctie T-2 (rev. 2):** de open workshop was in rev. 1 geprijsd op € 250/deelnemer
> (halve dag). Hoofdstuk 02 specificeert een volle dagcursus aan € 395–€ 450 p.p. De
> scenario's worden aangepast naar **€ 420/deelnemer** (middenpunt dagformat, 8 deelnemers
> gemiddeld = € 3.360 per workshop). De vorige prijs van € 250/halve dag is als format
> niet weerhouden in het definitieve aanbod.

| Parameter | Voorzichtig | Verwacht | Optimistisch |
|---|---|---|---|
| AI-analyses/jaar | **4** | **10** | **16** |
| Gem. prijs AI-analyse | € 750 | € 750 | € 750 |
| Omzet AI-analyses | € 3.000 | € 7.500 | € 12.000 |
| Sprints/kwartaal | 1 | 2 | 3 |
| Sprints/jaar | **4** | **8** | **12** |
| Gem. sprintprijs | € 3.500 | € 4.750 | € 5.500 |
| Omzet sprints | € 14.000 | € 38.000 | € 66.000 |
| Analyses die leiden tot sprint (conversieratio 40%) | 2 van 4 | 4 van 10 | 6 van 16 |
| In-company opleidingen/jaar (forfait € 2.000/dag) | 1 | 4 | 8 |
| Open workshops/jaar (gem. 8 pers. × € 420 = € 3.360) | 0 | 2 | 4 |
| Omzet opleidingen | € 2.000 | **€ 14.720** | **€ 29.440** |
| **Totale omzet/jaar** | **€ 19.000** | **€ 60.220** | **€ 107.440** |
| Btw-regime | Vrijgesteld | **Btw-plichtig (> €25.000)** | Btw-plichtig |

> **Toelichting verwacht scenario:** 10 analyses × € 750 = € 7.500; 8 sprints × € 4.750 =
> € 38.000; 4 in-company opleidingen × € 2.000 = € 8.000; 2 open workshops × 8 pers. ×
> € 420 = € 6.720. Totaal: **€ 60.220**. Dit ligt hoger dan de rev. 1 verwachting
> (€ 48.200) doordat de AI-analyse als aparte revenustream is toegevoegd én de
> opleidingsprijzen zijn gecorrigeerd naar de hogere dagformat-prijs.
>
> **Let op:** de verwacht-omzet van € 60.220 is jaar 2 of jaar 3 — niet het eerste jaar.
> In jaar 1 is een realistischer doel het voorzichtig scenario of het laagste
> verwacht-niveau (6–8 sprints, 6–8 analyses). Zie §8 voor cashflowtiming.

### 5.1 Scenario Voorzichtig — jaar 1

| Post | Bedrag |
|---|---|
| Omzet (4 analyses × €750 + 4 sprints × €3.500 + 1 in-company opl. × €2.000) | **€ 19.000** |
| − Vaste kosten | − € 4.230 |
| − Variabele kosten (4 sprints × €175 + 4 analyses × €50) | − € 900 |
| **= Netto belastbaar inkomen** | **€ 13.870** |
| − Sociale bijdragen (20,5% × €13.870) | − € 2.843 |
| **= Fiscaal inkomen** | **€ 11.027** |
| − Personenbelasting (45%, na aftrek soc.bijdr. als kost) | − € 4.122 |
| **= Netto beschikbaar** | **≈ € 6.905/jaar** ≈ **€ 575/maand** |
| Btw-regime | Vrijgesteld (< €25.000) |
| Sprints/kwartaal | 1 |

> Verbetering t.o.v. rev. 1 (€ 476/maand): de AI-analyses dragen € 3.000 extra omzet bij
> met lage variabele kosten, wat het nettoresultaat verbetert van € 476 naar € 575/maand.

### 5.2 Scenario Verwacht — jaar 2–3

| Post | Bedrag |
|---|---|
| Omzet (10 analyses × €750 + 8 sprints × €4.750 + 4 in-company × €2.000 + 2 open workshops × 8 pers. × €420) | **€ 60.220** |
| − Vaste kosten (inclusief btw-aangifte boekhouder ↑ €250) | − € 4.480 |
| − Variabele kosten (8 sprints × €175 + 10 analyses × €50) | − € 1.900 |
| **= Netto belastbaar inkomen** | **€ 53.840** |
| − Sociale bijdragen (20,5% × €53.840) | − € 11.037 |
| **= Fiscaal inkomen** | **€ 42.803** |
| − Personenbelasting (25%/40%/45% progressief, excl. belastingvrije som) | − € 15.200 (schatting) |
| **= Netto beschikbaar** | **≈ € 27.603/jaar** ≈ **€ 2.300/maand** |
| Btw-regime | Btw-plichtig (> €25.000) — 21% bovenop factuurprijs |

> Doel A (€ 1.500 netto/maand) **ruim bereikt** in verwacht scenario. Doel B (€ 4.000/mnd
> voltijds) nog niet bereikt in bijberoep; dat vereist het optimistisch scenario of de
> overstap naar hoofdberoep.

### 5.3 Scenario Optimistisch — jaar 3–4

| Post | Bedrag |
|---|---|
| Omzet (16 analyses × €750 + 12 sprints × €5.500 + 8 in-company × €2.000 + 4 open workshops × 8 pers. × €420) | **€ 107.440** |
| − Vaste kosten | − € 4.480 |
| − Variabele kosten (12 sprints × €175 + 16 analyses × €50) | − € 2.900 |
| **= Netto belastbaar inkomen** | **€ 100.060** |
| − Sociale bijdragen (20,5% t/m €75.024 + 14,16% op rest) | − € 18.949 |
| **= Fiscaal inkomen** | **€ 81.111** |
| − Personenbelasting (progressief + gemeentebelasting) | − € 33.300 (schatting) |
| **= Netto beschikbaar** | **≈ € 47.811/jaar** ≈ **€ 3.984/maand** |
| Btw-regime | Btw-plichtig |

> Doel B (€ 4.000/mnd voltijds) vrijwel bereikt. Tweekoppig team: per persoon ~€ 1.992/maand
> als inkomen gedeeld wordt — dit is het voltijds-signaal als beide partners full-time gaan.

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

### 7.1 De sprint en de AI-analyse zijn **niet** subsidieerbaar

De kmo-portefeuille dekt **opleiding**, niet implementatie/advies (behalve cybersecurity
advies). Een sprint is primair een implementatietraject. Een AI-analyse is een
adviestraject. Geen van beide zijn subsidieerbaar, ook niet na DV.O-registratie.

### 7.2 Opleidingen zijn subsidieerbaar — na DV.O

Enkel het opleidingsluik (dagcursus, in-company workshops, verdiepingsmodules) is
subsidieerbaar. Zolang de DV.O-registratie uitgesteld is, geldt dit niet.

**Aanbeveling wanneer DV.O wél rond is:** splits de factuur van een Sprint Standaard
(€ 4.750) in:
- Implementatie + begeleiding: € 3.500 (niet subsidieerbaar)
- Teamopleiding: € 1.250 (subsidieerbaar; kleine onderneming betaalt netto € 875)

Zo daalt de netto klantprijs voor het opleidingsluik van € 1.250 naar € 875 — een
**verkoopargument van € 375 subsidie zonder de implementatieprijs te verlagen.**

### 7.3 Maximaal subsidiebedrag

Klant kan max. € 7.500 subsidie per jaar ontvangen. Bij een in-company dagcursus van
€ 2.000 recupereert de kleine klant € 600 (30% subsidie) — duidelijk communiceerbaar.

> Herhaling: dit alles is pas geldig **na afronding DV.O-registratie**. Zolang die er
> niet is, spreekt Auxilia altijd in de toekomende tijd.

---

## 8. Cashflowplanning jaar 1

### 8.1 Betalingsgedrag kmo's en aanbevolen betalingsstructuur

**AI-analyse:**

| Fase | Aanpak |
|---|---|
| Offerte getekend | **100% vooraf** of 50% bij start / 50% bij rapport |
| Betalingstermijn | Max. **15 dagen** (korte opdracht) |

Cashflowvoordeel: de analyse genereert direct inkomsten, vóór een sprint van start gaat.

**Sprint:**

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

### 8.2 Rol van de AI-analyse als cashflowbuffer

De AI-analyse lost een structureel cashflowprobleem op:
- Een sprint duurt 4–8 weken; de eerste betaling in een kwartaal kan dus laat vallen.
- Analyses kosten ~5,5 uur per stuk en worden snel afgerond (1–2 weken).
- In een kwartaal zonder sprint-start kan Auxilia 2–3 analyses doen: **€ 1.500 – € 2.250
  extra cashflow** tegen lage inspanning.
- De analyses kwantificeren zichzelf deels: uit 10 analyses in het verwacht scenario
  leiden er 4 tot een sprint (conversieratio 40%) — dit is de **bottom-of-funnel
  voeding** die het sprintvolume op peil houdt.

### 8.3 Kwartaalcashflow jaar 1 (verwacht scenario: jaar 1 transitie)

Aanname jaar 1 transitie: 2 sprints/kwartaal + 2–3 analyses/kwartaal (oplopend volume).

| Kwartaal | Sprints | Analyses | Omzet (incasso) | Vaste kosten | Sociale bijdragen (voorlopig) | Netto cashflow |
|---|---|---|---|---|---|---|
| Q1 | 2 × € 4.750 | 2 × € 750 | € 11.000 | € 1.057 | € 409 | **€ 9.534** |
| Q2 | 2 × € 4.750 | 3 × € 750 | € 11.750 | € 1.057 | € 409 | **€ 10.284** |
| Q3 | 2 × € 4.750 | 3 × € 750 | € 11.750 | € 1.057 | € 409 | **€ 10.284** |
| Q4 | 2 × € 4.750 | 2 × € 750 | € 11.000 | € 1.057 | € 409 | **€ 9.534** |
| **Jaar 1 totaal** | 8 sprints | 10 analyses | **€ 45.500** | **€ 4.230** | **€ 1.636** | **€ 39.634** |
| **Belastingprovision (45%)** | | | | | | **− € 15.856** |
| **Netto beschikbaar** | | | | | | **≈ € 23.778** ≈ **€ 1.982/maand** |

> **Let op:** btw-herberekening sociale bijdragen 2 jaar later. Plan een aparte buffer
> van **€ 200 – € 300/maand** voor de definitieve bijdrageafrekening.
>
> **Btw:** bij het jaar-1 transitiescenario passeert de omzet (€ 45.500) ruimschoots de
> € 25.000-drempel. Zodra die drempel gepasseerd is: btw aanrekenen op nieuwe facturen,
> kwartaalaangifte indienen. Gesprek met boekhouder plannen in Q1 over optimale timing.

---

## 9. Gevoeligheidsanalyse: kritische aannames

De scenario's draaien op een beperkt aantal aannames die de uitkomst sterk bepalen.
Hieronder staan de drie gevoeligste, met wat er verandert als ze meevallen of tegenvallen.

| Aanname | Planwaarde | Pessimistisch | Optimistisch | Impact op netto/mnd |
|---|---|---|---|---|
| **G: conversieratio analyse → sprint** | 40% | 20% (1 op 5) | 60% (3 op 5) | Bij 20%: –€ 6.000 omzet verwacht scenario; bij 60%: +€ 6.000 |
| **F: prijs AI-analyse** | € 750 | € 500 (lanceringsprijs) | € 950 (meer diepgang) | Verwacht scenario: ±€ 2.500/jaar verschil bij 10 analyses |
| **C: sprintvolume** | 8 sprints/jaar (verwacht) | 5 sprints/jaar | 10 sprints/jaar | ±€ 14.250 omzet per sprint verschil bij € 4.750 gem. |
| **Opleidingsvraag** | 4 in-company/jaar (verwacht) | 1 (moeilijk te verkopen zonder DV.O-argument) | 6 | ±€ 10.000 omzet verschil |

**Meest risicovolle aanname:** de conversieratio analyse → sprint (aanname G, 40%). Als
dit niet uitkomt, genereert de AI-analyse voornamelijk cashflow zonder het sprint-volume
te voeden. Dan zijn de analyses waardevoller als zelfstandig product dan als funnel.
Cedric moet dit in het eerste kwartaal meten en eventueel de sprint-propositie aanscherpen.

---

## 10. Samenvatting kerncijfers

| Indicator | Voorzichtig | Verwacht | Optimistisch |
|---|---|---|---|
| Jaaromzet | € 19.000 | € 60.220 | € 107.440 |
| Netto beschikbaar | ≈ € 6.905 | ≈ € 27.603 | ≈ € 47.811 |
| Netto/maand | ≈ € 575 | ≈ € 2.300 | ≈ € 3.984 |
| Sprints/jaar | 4 | 8 | 12 |
| AI-analyses/jaar | 4 | 10 | 16 |
| In-company opleidingen/jaar | 1 | 4 | 8 |
| Open workshops/jaar | 0 | 2 | 4 |
| Btw-regime | Vrijgesteld | Plichtig (> €25.000) | Plichtig |
| Break-even (kosten) | 2 sprints | 1–2 sprints | 1 sprint |
| Doel A bereikt (€1.500/mnd)? | **Nee** | **Ja (€ 2.300)** | Ruim ja |
| Doel B bereikt (€4.000/mnd voltijds)? | Nee | Nee (€ 2.300) | **Vrijwel (€ 3.984)** |

---

## 11. Bronnenlijst

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
| AI voor KMO — AI-scan prijs | https://aivoorkmo.be/ | 2026-06-12 |
| AI Learning — open sessie prijs | https://ailearning.be/ | 2026-06-12 |
| Syntra AB — AI-agents prijs | https://www.syntra-ab.be/opleidingen/ai-agents-bouw-je-eigen-digitale-collegas-zonder-een-regel-code | 2026-06-12 |
| Algida — freelance tarieven 2025 | https://algida.be/freelance-tarieven-2025/ | 2026-06-12 |
| Elivado — Claude AI kosten | https://elivado.nl/claude-ai-kosten/ | 2026-06-12 |
| Acerta — verzekering gewaarborgd inkomen | https://www.acerta.be/nl/inspiratie/verzekering-gewaarborgd-inkomen-prijs | 2026-06-12 |
| Practicali — kleine ondernemingsregeling omzetmelding | https://www.practicali.be/blog/kleine-ondernemingsregeling-nieuwe-omzetmelding-via-de-klantenlisting-uiterlijk-op-31-maart-2026 | 2026-06-12 |
