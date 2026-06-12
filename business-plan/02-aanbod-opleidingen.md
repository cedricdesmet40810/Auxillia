# 02 — Aanbod & Curriculum Opleidingen

Eigenaar: opleidingsontwerper
Laatst bijgewerkt: 2026-06-12 (rev. 2 — beslissingen 2026-06-12 verwerkt)

> `business-plan/01-markt.md` bestaat nog niet op het moment van schrijven. Zodra dat
> hoofdstuk beschikbaar is, moeten de concurrentieanalyse in §6 en de differentiatie in
> §6.3 herijkt worden op basis van de marktgegevens.

> **Wijzigingslog rev. 2 (2026-06-12):** drie beslissingen van Cedric verwerkt:
> (a) de betaalde AI-analyse is het kerninstapproduct — de gratis kennismakingssessie
> (vroeger Niveau 1 van de leerladder) is daarmee niet langer de primaire lead-generator;
> (b) cursussen blijven als derde poot bestaan, zonder vereiste registratie;
> (c) DV.O-registratie uitgesteld — kmo-portefeuille-subsidie is off-the-table op korte
> termijn; alle subsidie-argumenten in de klantcommunicatie over opleidingen zijn geschrapt
> of geconditioneerd; auditbestendig materiaal blijft ontworpen als voorbereiding op een
> mogelijke toekomstige registratie.

---

## 0. Scope van dit hoofdstuk

Dit hoofdstuk beschrijft het volledige opleidingsaanbod van Auxilia: de basisopleiding "AI
voor kmo's", de verschillende deliveryformats, de leerladder van kennismaking tot
verdieping, het benodigde lesmateriaal, de auditbestendigheid voor kmo-portefeuille, de
positionering ten opzichte van concurrenten, en de didactische principes achter het ontwerp.

Het **opleidingsaanbod is de derde poot** naast de AI-analyse (instapproduct) en de sprint
(kernaanbod). Cursussen hoeven geen DV.O-registratie om verkocht te worden — ze worden
aangeboden tegen volle marktprijs, zonder subsidiebelofte aan de klant.

De **sprint** (procesautomatisering met vaste prijs en vaste deadline) valt buiten dit
hoofdstuk maar heeft een raakvlak: elke sprint bevat een opleidingsluik voor het team. Dat
luik moet naadloos aansluiten op de hier beschreven modulaire structuur.

De **AI-analyse** (zie `00-context.md`) is het primaire instapproduct en leidt funnel-matig
naar de sprint. Hoe de leerladder van de cursussen zich verhoudt tot die funnel is uitgewerkt
in §4.

---

## 1. Basisopleiding "AI voor kmo's"

### 1.1 Doelgroep

Kmo-medewerkers **zonder technische achtergrond**: zaakvoerders, bedienden, administratief
medewerkers, salesprofielen, HR, projectopvolgers. Ze kennen ChatGPT misschien van naam,
maar gebruiken het niet structureel in hun werk. Ze zijn niet geïnteresseerd in hoe AI
werkt; wel in wat het hen de dag erna bespaart.

Aanname (zie open vraag in `00-context.md`): gemiddeld 5–15 deelnemers per sessie, uit
dezelfde onderneming of uit meerdere kmo's in een open format.

### 1.2 Cursusnaam (werktitel)

**"AI die werkt — voor jouw job"**
Ondertitel: *Een praktische dagcursus voor kmo-medewerkers*

### 1.3 Structuur: 4 modules, 1 dag (6 contacturen)

De cursus is één volledige dag. Elke module duurt 1,5 uur, met twee pauzes van 15 minuten
en een middagpauze van 45 minuten (totale aanwezigheid: ±8 uur, 6 uur netto leertijd).

---

#### Module 1 — Wat AI wél en niet kan (1,5 uur)

**Leerdoelen**
Na afloop kan de deelnemer:
- het verschil uitleggen tussen generatieve AI (ChatGPT, Copilot, Claude) en automatisering
- minstens drie concrete toepassingen noemen die passen bij zijn/haar functie
- twee situaties noemen waarbij AI fout of onbetrouwbaar is en wat je dan doet

**Werkvorm**
- *Opening*: iedere deelnemer schrijft op een sticky: "Ik gebruik nu al AI voor…" en "Ik
  ben bang dat AI…". Verwerking in groep (5 min).
- *Demorondes*: live demo van ChatGPT, Microsoft Copilot, en Gemini op een alledaagse
  opdracht (e-mail schrijven, samenvatten, berekening), met verrassingsfouten die de groep
  moet ontdekken.
- *Patroonkaart*: deelnemers vullen een sjabloon in (3 kolommen: "AI doet dit goed /
  matig / slecht voor mijn job"). Wordt bewaard als persoonlijk naslagwerk.

**Materiaal**
- Flip-over, sticky notes
- Demo-laptop met live internet
- Patroonkaart (A4, printklaar)
- Geen slides in deze module — demonstratie gaat voor theorie

---

#### Module 2 — Prompts die werken (1,5 uur)

**Leerdoelen**
Na afloop kan de deelnemer:
- een driedelig prompt schrijven (context – taak – formaat) voor een eigen werktaak
- een zwak antwoord van AI herkennen en bijsturen via een vervolgprompt
- minimaal één promptsjabloon aapassen voor zijn/haar functie

**Werkvorm**
- *Promptformule*: introduceer C-T-F (Context – Taak – Formaat) aan de hand van één
  voorbeeld dat iedereen kent (sollicitatiemail weigeren).
- *Duo-oefening*: deelnemers kiezen een eigen werktaak en schrijven in duo een prompt.
  Wisselen van laptop: de ander beoordeelt de output.
- *Promptbibliotheek starten*: elke deelnemer voegt zijn beste prompt toe aan een
  gedeeld document (Google Docs of Word) — dit is het begin van de bedrijfseigen
  promptbibliotheek.

**Materiaal**
- Laptops of tablets (BYOD — bring your own device)
- Promptsjabloon-werkblad (A4)
- Gedeeld document voor promptbibliotheek (trainer bereidt dit voor)

---

#### Module 3 — AI in jouw dagelijkse processen (1,5 uur)

**Leerdoelen**
Na afloop kan de deelnemer:
- twee processen uit de eigen werkdag benoemen die AI-assistentie verdienen
- een eenvoudige workflow uitschrijven: trigger → AI-stap → menselijke controle → output
- grenzen stellen: welke data mag je wél en niet in een AI-tool invoeren

**Werkvorm**
- *Proceskaart*: deelnemers tekenen hun dagindeling als stroom van taken (30 min). Samen
  met de trainer markeren ze "AI-kansen" en "no-go zones" (privacy, vertrouwelijkheid).
- *Live workflow bouwen*: de trainer bouwt live een eenvoudige workflow (bv. klantmail
  ontvangen → samenvatten met AI → categoriseren → conceptantwoord genereren) in het tool
  dat de groep al kent (Copilot in Outlook of ChatGPT).
- *Terugkoppeling*: elke deelnemer formuleert één concrete actie voor morgen.

**Materiaal**
- Proceskaart-sjabloon (A4 of flip-over vel)
- Overzicht "wat mag niet in AI-tools" (GDPR-cheatsheet, 1 pagina)

---

#### Module 4 — Kritisch gebruiken & volgende stappen (1,5 uur)

**Leerdoelen**
Na afloop kan de deelnemer:
- hallucinaties en biases herkennen en een verificatiestrategie toepassen
- de EU AI Act samenvatten in drie zinnen (op gebruikersniveau: geen juridisch detail)
- een persoonlijk 30-dagen-plan invullen voor het inbedden van AI in de eigen job

**Werkvorm**
- *Fouten-challenge*: de trainer legt vijf AI-outputs voor (feitelijk fout, verouderd,
  bevooroordeeld, geknipt uit context, prima). Deelnemers stemmen en bespreken.
- *Vertrouwensladder*: groepsgesprek — "Wanneer vertrouw jij AI blindelings? Wanneer niet?"
  Koppel aan een eenvoudige beslisregel: "Hoe hoger de impact, hoe meer je verifieert."
- *30-dagen-kaart*: elke deelnemer vult een persoonlijke actiekaart in (twee AI-taken die
  ze de komende 30 dagen willen integreren, inclusief hoe ze de tijdwinst zullen meten).
  Dit is ook de meetbasis voor de follow-up (zie §7).

**Materiaal**
- Vijf fout-slides (beamer of groot scherm)
- 30-dagen-actiekaart (A5, dubbelzijdig — kant 1: commitments, kant 2: meetrubriek)

---

### 1.4 Benodigde infrastructuur

| Element | Minimum | Ideaal |
|---|---|---|
| Lokaal | Tafelgroepen, geen klassieke rijen | U-opstelling of eilandtafels |
| Scherm | Beamer of groot TV-scherm | Interactief scherm |
| Internet | Stabiele wifi voor alle deelnemers | Eigen hotspot als backup |
| Devices | BYOD (deelnemers brengen laptop mee) | Reserve laptops trainer |
| Software | ChatGPT (gratis tier volstaat), Copilot of Claude | — |

**Aanname**: in-company sessies vinden doorgaans in de vergaderruimte van de klant plaats.
Open workshops in een huurlokaal (bv. Voka-lokalen, co-working, gemeentehuis). ❓ Cedric
moet beslissen of Auxilia een vast samenwerking aangaat met een locatiepartner in de Kempen.

---

## 2. Deliveryformats

### 2.1 Overzicht van de vier formats

| Format | Beschrijving | Doelgroep | Prijs (excl. btw) |
|---|---|---|---|
| **Open workshop** | Dagcursus voor max. 12 deelnemers uit verschillende kmo's | Individuele deelnemers of kleine bedrijven zonder eigen groep | €395–€450 p.p. |
| **In-company** | Zelfde dagcursus, exclusief voor één bedrijf (6–15 deelnemers) | Kmo's die samen hun team willen opleiden | €1.800–€2.400 per dag |
| **Opleidingsluik sprint** | Halve dag (3 uur), ingebakken in een automatiseringssprint | Medewerkers die met het geautomatiseerde proces gaan werken | Inbegrepen in sprintprijs |
| **Abonnement / doorlopend** | Maandelijks 2 uur update + Q&A-sessie (online) | Terugkerende klanten die al een basis hebben | €149–€199 p.m. per bedrijf |

> **Opmerking prijsbepaling**: alle prijzen zijn volle marktprijzen exclusief btw, **zonder
> subsidiekorting**. Zolang Auxilia geen DV.O-nummer heeft, kan de klant géén
> kmo-portefeuille aanvragen voor deze opleidingen. Communiceer dat eerlijk en proactief:
> "Onze opleidingen zijn momenteel niet subsidieerbaar via de kmo-portefeuille. We zijn de
> registratieprocedure aan het voorbereiden — zodra dat rond is, informeren we je."

### 2.2 Analyse per format

**Open workshop**
- Voordelen: lage drempel voor kleine bedrijven, netwerkmogelijkheid tussen deelnemers,
  schaalbaar (meerdere sessies per maand plannen), meerdere kmo's per sessie amortiseren de
  kosten.
- Nadelen: homogeniteit is lager (deelnemers uit andere sectoren), minder diepgaande
  aanpak op de eigen processen, hogere voorbereidingstijd voor de trainer (geen specifiek
  bedrijfscontex).
- kmo-portefeuille: **niet beschikbaar op korte termijn** (DV.O-registratie uitgesteld).
  Voorbereid voor latere subsidiabiliteit zodra registratie alsnog doorgaat — zie §3.
- Aanbeveling: starten met open workshops in de Kempen om zichtbaarheid te bouwen en
  feedback te verzamelen. Lage drempel; ideaal als lanceringsinstrument. Verkoopargument
  is de directe praktijkwaarde, niet de subsidie.

**In-company**
- Voordelen: trainer kan de processen van het bedrijf centraal stellen, hogere impact,
  hogere prijs per dag, eenvoudiger aanwezigheidsregistratie (audit), sterker referentie.
- Nadelen: vraagt prospectie per bedrijf, tijdsinvestering voor voorbereiding (intake
  nodig), weinig schaalbaar als bijberoep met beperkt beschikbare uren.
- kmo-portefeuille: **niet beschikbaar op korte termijn** (DV.O-registratie uitgesteld).
  Auditbestendig materiaal is al ontworpen (zie §3) — de sprong naar subsidiabiliteit
  is in principe beperkt tot het afronden van de registratieprocedure.
- Aanbeveling: de meest waardevolle route op middellange termijn. Starten zodra de
  basiscursus bewezen is (eerste 2–3 open workshops als piloot). Instap via de
  AI-analyse-funnel is de logische route: analyse → rapport → in-company opleiding
  voor het team of sprint (afhankelijk van de bevinding in het rapport).

**Opleidingsluik sprint**
- Voordelen: natuurlijke upsell, deelnemers zijn gemotiveerd (ze gaan het tool de volgende
  dag gebruiken), hoge relevantie (training op het geautomatiseerde proces).
- Nadelen: beperkt tot het geautomatiseerde proces; geen brede AI-geletterdheid.
- kmo-portefeuille: **niet beschikbaar op korte termijn**. Aparte facturatie van het
  opleidingsluik heeft op dit moment geen subsidievoordeel voor de klant; het vereenvoudigt
  wel de boekhouding als het luik later subsidieerbaar wordt. ❓ Cedric beslist of het
  apart gefactureerd wordt of in de sprintprijs vervat zit.
- Aanbeveling: altijd een formeel opleidingsluik opnemen in elke sprint, ook al is het
  kort. Het verhoogt de perceptiewaarde en bereidt de documentatie voor op een mogelijke
  latere subsidieclaim.

**Abonnement / doorlopend**
- Voordelen: terugkerende omzet, klantenbinding, aansluitend op snelle evolutie van AI-
  tools (maandelijkse updates zijn voor kmo's waardevol), lage tijdsinvestering per sessie.
- Nadelen: vereist schaalbare online infrastructuur (Zoom/Teams, opnames), moeilijk
  subsidieerbaar via kmo-portefeuille (format sluit niet goed aan op dossierstructuur).
- Aanbeveling: pas lanceren na de eerste 5–10 klanten die al een basis hebben via de
  dagcursus of sprint. Als tweede fase. Prijspunt van €149–€199/maand is vergelijkbaar met
  een SaaS-abonnement — goed te rechtvaardigen als "AI-abonnement voor je team".

### 2.3 Aanbeveling volgorde

> **Gewijzigd in rev. 2**: de primaire funnel loopt via de AI-analyse, niet via de
> kennismakingssessie. De volgorde hieronder houdt daarmee rekening.

1. **Maand 1–3**: open workshops als piloot (1 per maand, max. 12 deelnemers, Kempen) —
   ook als zichtbaarheidsinstrument naast de AI-analyse-funnel. Geen subsidiebelofte.
2. **Maand 1–3 (parallel)**: elke opgeleverde AI-analyse bevat een standaard
   opleidingsaanbeveling; eerste in-company dagcursussen als direct gevolg van
   analyse-rapporten.
3. **Maand 4–6**: in-company sessies schalen op basis van analyse-pipeline en referenties
   uit de open workshops.
4. **Maand 6+**: opleidingsluik systematisch koppelen aan elke sprint (altijd inbegrepen,
   apart gedocumenteerd voor latere subsidiabiliteit).
5. **Maand 12+**: abonnementsformule lanceren voor terugkerende klanten.
6. **Overweeg DV.O-registratie** zodra ≥5 betalende cursusklanten bewezen zijn — zie §9.

---

## 3. Eisen kmo-portefeuille en VLAIO-audit — voorbereid maar uitgesteld

> **Status (beslissing 2026-06-12)**: de DV.O-registratie is **voorlopig uitgesteld**.
> Kmo-portefeuillesubsidie is daarmee off-the-table op korte termijn en mag **niet**
> beloofd worden aan klanten. Klantcommunicatie: "Onze opleidingen zijn momenteel niet
> subsidieerbaar via de kmo-portefeuille. We bereiden de registratie voor en informeren
> je zodra dat verandert."
>
> De inhoud van dit hoofdstuk (registratieprocedure, kmop-norm, auditbestendig materiaal)
> blijft bewaard als **voorbereiding** voor de registratie zodra Auxilia die opportuun acht.
> Geen actiepunt op korte termijn — wel een activeerbare springplank.
>
> Intern voordeel van de auditbestendige aanpak: de documentatiegewoonten (aanwezigheidslijst,
> evaluatieformulier, attest) zijn hoe dan ook professioneel en versterken de geloofwaardigheid.

### 3.1 Registratieprocedure in het kort

Auxilia moet een audit doorlopen bij een erkend auditbureau (bv. Bureau Veritas, DNV,
Certup, BQA) om een DV.O-nummer te ontvangen. VLAIO registreert dienstverleners voor een
periode van **5 jaar** op basis van het auditrapport.

**Startende dienstverleners** (zoals Auxilia) doorlopen een **beperkte startaudit**:
- Vrijgesteld van twee eisen: bewijs van ervaring en klantentevredenheidssurvey
- Na goedkeuring: registratie voor **2 jaar**
- Na 2 jaar: follow-up audit met toetsing van opgedane ervaring en klantentevredenheid
- Na positieve follow-up: registratie voor de resterende 3 jaar (totaal 5 jaar)

Bronnen: [Registratieprocedure dienstverleners | VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/kmo-portefeuille-voor-dienstverleners/de-registratieprocedure-voor-dienstverleners) (geraadpleegd 2026-06-12); [Hoe verloopt een audit | VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/kmo-portefeuille-voor-dienstverleners/de-registratieprocedure-voor-dienstverleners/hoe-0) (geraadpleegd 2026-06-12)

### 3.2 De 5 basiseisen van de kmop-norm

De kmop-norm bevat vijf basisvereisten waaraan een geregistreerde dienstverlener moet
voldoen. De auditor toetst elke eis aan de hand van concrete indicatoren.

| Eis | Wat de auditor controleert |
|---|---|
| **1. Activiteit** | Is het duidelijk wat je precies aanbiedt? Heb je voldoende mensen en middelen om die activiteit uit te voeren? |
| **2. Ervaringsbewijs** | Kan je aantonen dat je ervaring hebt in het domein? (Vrijgesteld bij startaudit) |
| **3. Klantentevredenheid** | Meet je systematisch de tevredenheid van je klanten? (Vrijgesteld bij startaudit; vereist na 2 jaar) |
| **4. Kennis van het steuninstrument** | Ken je de kmo-portefeuille-regels (subsidiabele thema's, aanvraagtermijn van 14 dagen, factuurvereisten)? |
| **5. Integriteit** | Geen belangenconflicten, transparante communicatie, geen misbruik van het subsidiesysteem |

Bronnen: [Registratiemethode | VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/kmo-portefeuille-voor-dienstverleners/de/de) (geraadpleegd 2026-06-12); [Certup — voorbereidingsdocumenten audit](https://certup.be/nl/kmop-audit-voorbereidingsdocumenten/) (geraadpleegd 2026-06-12)

### 3.3 Subsidieerbaar thema

AI-opleidingen vallen onder het thema **Digitalisering** van de kmo-portefeuille. Dat thema
omvat "digitale technologieën, innovaties en data die leiden tot nieuwe activiteiten of
wijzigingen in bestaande activiteiten op het vlak van artificiële intelligentie (AI),
hardware, software, online toepassingen en cybersecurity."

ChatGPT-workshops, Copilot-trainingen en brede AI-geletterdheidsopleidingen zijn
subsidieerbaar onder dit thema. Subsidiepercentages (kleine ondernemingen 30%, middelgrote
20%) zijn ongewijzigd gebleven na de hervorming van 1 februari 2026.

Bron: [Subsidieerbare diensten | VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/kmo-portefeuille-voor-dienstverleners/subsidieerbare-diensten) (geraadpleegd 2026-06-12); [Digitalisering | VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/wat-is-de-kmo-portefeuille/digitalisering) (geraadpleegd 2026-06-12)

### 3.4 Aanvraagtermijn voor de klant

Een subsidieaanvraag moet ingediend worden **binnen 14 kalenderdagen na de startdatum van
de opleiding**. Dit is een harde grens: informeer klanten altijd proactief en bij voorkeur
vóór de eerste sessie.

Praktische implicatie: vermeld in elke opdrachtbevestiging en factuur de startdatum van de
opleiding expliciet, zodat de klant zijn aanvraag op tijd kan indienen.

Bron: [Subsidies aanvragen en ontvangen | VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/subsidies-aanvragen-en-ontvangen) (geraadpleegd 2026-06-12)

### 3.5 Auditbestendig lesmateriaal — checklist per opleiding

De volgende documenten moeten **per opleiding aangemaakt en bewaard worden** om een audit te
doorstaan. Bewaar ze minstens **5 jaar** (vereiste bij herregistratie: lijst van alle
kmo-portef.-dossiers van de afgelopen 5 jaar).

| Document | Inhoud | Wanneer aanmaken |
|---|---|---|
| **Aanwezigheidslijst** | Naam, functie, handtekening deelnemer, datum en duur sessie | Op de dag zelf (papier of digitaal) |
| **Evaluatieformulier** | Tevredenheid (schaal), leerdoelen gehaald, suggesties | Aan het einde van elke sessie |
| **Attest van deelname** | Naam deelnemer, naam opleiding, datum, duur, naam dienstverlener, DV.O-nr | Binnen 5 werkdagen na afloop per mail |
| **Opdrachtbevestiging** | Omschrijving opleiding, startdatum, prijs, btw-nr klant | Vóór aanvang |
| **Factuur** | Conform btw-vereisten; vermeld thema "Digitalisering" en kmo-portef.-referentie | Na afloop |
| **Syllabus / cursusmateriaal** | Inhoudsbeschrijving, leerdoelen, duur per module | Bij voorbereiding; bewaar versie per datum |
| **Klantentevredenheidssurvey** | Samenvattend rapport van evaluatieformulieren | Na iedere reeks sessies (vereist na 2 jaar) |

**Digitale aanpak**: gebruik een standaard Google Form voor evaluatie en aanwezigheid;
exporteer na elke sessie naar PDF en sla op in een map per klant-per-datum. Dit volstaat
voor een audit.

---

## 4. Leerladder

### 4.1 Overzicht en verhouding tot de AI-analyse-funnel

De leerladder heeft vier niveaus. **Cruciaal contextverschil t.o.v. rev. 1**: de betaalde
AI-analyse (instapproduct van Auxilia, zie `00-context.md`) is nu de primaire
lead-generator en funnel-ingang — niet de gratis kennismakingssessie.

Dit heeft gevolgen voor hoe de niveaus samenhangen:

```
Niveau 4 — AI-strategie & automatisering (halve dag + coachingsessie)
    ↑
Niveau 3 — Verdieping: sector-specifieke toepassingen (dagmodule)
    ↑
Niveau 2 — Basisopleiding "AI die werkt" (1 dag — zie §1)
    ↑
Niveau 1a — Kennismakingssessie (2 uur, gratis/symbolisch) ← lage-drempel lead voor wie
              NIET via de analyse binnenkomt (bv. open evenement, netwerk, mond-tot-mond)
Niveau 1b — Kennismaking via AI-analyse-rapport ← primaire instappers (aanbeveling in
              rapport kan rechtstreeks doorverwijzen naar N2 of naar sprint-opleidingsluik)
```

**Funnel-logica**:
- Klant doorloopt AI-analyse → rapport → sprint-voorstel.
- In het rapport kan Auxilia ook een opleidingsaanbeveling opnemen voor het team
  ("jullie medewerkers hebben baat bij de basiscursus AI vóór of kort na de sprint").
- Zo wordt de dagcursus een **aanbeveling vanuit het rapport**, met hogere conversiekans
  dan een koude inschrijving vanuit een evenement.
- De gratis kennismakingssessie (N1a) blijft zinvol als zelfstandig lanceringsinstrument
  voor zichtbaarheid in de Kempen, maar is niet meer de hoofdingang van de funnel.

### 4.2 Niveau 1a — Kennismakingssessie (2 uur)

**Doel**: lokale zichtbaarheid opbouwen, laagdrempelige instap voor wie nog niet klaar
is voor een betaalde analyse, mond-tot-mondreclame creëren.

**Inhoud**: live demo van 3 AI-toepassingen op vertrouwde werktaken, Q&A, korte uitleg
over de AI-analyse als volgende stap.

**Subsidie**: niet vermelden — DV.O-registratie uitgesteld.

**Format**: open evenement (bv. bij Voka, Unizo-lokaal of gemeentehuis Kempen), max.
25 personen. Kan ook online (Teams-webinar).

**Prijs**: gratis of €25 symbolisch bijdrage (dekt zaalhuur).

**Overgang**: deelnemers ontvangen informatie over de AI-analyse als betaalde vervolgstap
(€750 richtprijs) én een kortingscode van €50 op de dagcursus als ze direct inschrijven.

### 4.3 Niveau 1b — Kennismaking via AI-analyse-rapport

Dit is geen aparte sessie maar een **aanbeveling in het analyserapport**. Als de analyse
aantoont dat het team baat heeft bij brede AI-geletterdheid vóór of naast een sprint,
vermeldt het rapport expliciet: "Wij adviseren een in-company dagcursus voor jullie team."
Dat rapport-voorstel is de meest warme en geloofwaardige instap naar N2.

### 4.4 Niveau 2 — Basisopleiding (1 dag)

Volledig beschreven in §1.

**Overgang naar N3**: deelnemers die de 30-dagen-actiekaart invullen en na 30 dagen een
korte follow-up invullen (zie §7), ontvangen een uitnodiging voor de verdiepingsmodule.

### 4.5 Niveau 3 — Verdiepingsmodule (dagdeel = 3 uur)

Sector-specifieke of functie-specifieke AI-toepassingen. Voorbeelden:

| Module | Doelgroep | Inhoud |
|---|---|---|
| AI voor administratie & planning | Bedienden, office managers | Outlook/Copilot diepgaand, Excel AI-functies, AI-gestuurde agenda-optimalisatie |
| AI voor verkoop & klantcontact | Salesprofielen | Offerte-generatie met AI, klantmails personaliseren, CRM-data analyseren |
| AI voor rapportering & cijfers | Zaakvoerders, financieel medewerkers | Data-analyse met ChatGPT, automatisch dashboard, samenvatting jaarverslagen |
| AI voor productie & logistiek | Magazijnopleiders, planners | Predictief onderhoud concepten, AI voor inkoopplanning, veiligheids- en kwaliteitscontrole |

**Prijs**: €295–€345 p.p. (open) of €900–€1.200 (in-company halve dag)

**Overgang naar N4**: deelnemers die een verdiepingsmodule volgden én al een sprint
deden (of aan het doen zijn), kunnen deelnemen aan het strategieniveau.

### 4.6 Niveau 4 — AI-strategie & automatisering (halve dag + coaching)

**Doel**: zaakvoerder of leidinggevende helpen een AI-routekaart te maken voor hun bedrijf.

**Inhoud**:
- Inventarisatie van AI-kansen in het bedrijf (proceskaart)
- Prioritering: impact vs. implementatiegemak
- Berekening van potentiële tijdwinst en ROI
- Concrete volgende stap definiëren (bv. een sprint)

**Format**: halve dag groepsessie (max. 6 zaakvoerders) + individueel coachgesprek van 1 uur.

**Prijs**: €595 p.p. (open) of op aanvraag in-company

**Overgang**: directe ingang naar een sprinttraject.

---

## 5. Lesmateriaal per format

### 5.1 Minimaal auditbestendig materiaalset

Elke opleiding, ongeacht format, moet de volgende materialen bevatten en bewaren:

| Materiaal | Format | Bewaartermijn |
|---|---|---|
| Syllabus (inhoud + leerdoelen + duur) | PDF, gedateerd | 5 jaar |
| Aanwezigheidslijst | PDF of digitaal (getekend) | 5 jaar |
| Evaluatieformulier (per deelnemer) | Digitaal (Google Form export) | 5 jaar |
| Attest van deelname | PDF per deelnemer | 5 jaar |
| Factuur | Conform btw-wetgeving | 7 jaar (boekhoudkundige verplichting) |
| Opdrachtbevestiging | PDF per klant | 5 jaar |

### 5.2 Lesmateriaal voor de deelnemer

| Materiaal | Wanneer uitreiken | Doel |
|---|---|---|
| Patroonkaart (AI kan / kan niet) | Module 1 | Persoonlijk naslagwerk |
| Promptsjabloon-werkblad | Module 2 | Oefenen + mee naar huis |
| GDPR-cheatsheet AI-gebruik | Module 3 | Praktische no-go-lijst |
| 30-dagen-actiekaart | Module 4 | Gedragsverandering en follow-up |
| Promptbibliotheek (deelnemersversie) | Einde dag | Herbruikbaar op het werk |

### 5.3 Materiaal voor de trainer

| Materiaal | Beschrijving |
|---|---|
| Trainershandleiding per module | Tijdlijn, instructies per werkvorm, alternatieven bij uitval internet |
| Presentatiedeck (beamer) | Maximaal 20 slides; geen bullets-theorie, alleen demo-schermen en visuele instructies |
| Reserveoefeningen | Twee backup-oefeningen per module voor groepen die sneller werken |
| Intakeformulier (in-company) | Te versturen 1 week voor de sessie: sector, tools die het bedrijf al gebruikt, specifieke vragen |

### 5.4 Digitale infrastructuur

Minimale digitale stack (bijberoep-vriendelijk, lage kost):

| Tool | Gebruik | Kost |
|---|---|---|
| Google Forms | Aanwezigheid + evaluatie | Gratis |
| Google Drive (gedeelde map per klant) | Archief per opleiding | Gratis (15 GB) of Workspace €6/maand |
| Canva of Google Slides | Presentaties | Gratis |
| Brevo of Mailchimp | Attest van deelname versturen | Gratis tier volstaat bij < 300 mails/maand |

---

## 6. Concurrentieanalyse & differentiatie

> **Aantekening**: `business-plan/01-markt.md` bestaat nog niet. De analyse hieronder is
> gebaseerd op eigen webonderzoek (2026-06-12). Herijking nodig zodra de marktonderzoeker
> zijn hoofdstuk publiceert.

### 6.1 Kaart van het concurrerende landschap

| Aanbieder | Type aanbod | Formaat | Prijs (indicatief) | Zwakte voor kmo-niche |
|---|---|---|---|---|
| **Cevora** | AI-geletterdheid (basis t/m strategisch), ChatGPT, prompting, GPT's bouwen | Online mini-cursussen, gratis webinars, in-company | Gratis voor medewerkers uit bepaalde PC's | Alleen toegankelijk voor bepaalde paritaire commissies; geen maatwerk per bedrijfsproces |
| **Syntra AB** | "AI voor de management assistent" (6u/2 sessies), Data & AI-pad | Open campus, campus-gebonden (Antwerpen) | €395–€477 incl. btw | Campusgebonden, sectorbreed (niet kmo-specifiek); geen focus op de eigen processen |
| **SBM** | Breed AI-palet: ChatGPT beginners, Copilot, AI voor financiën, HR, productie | Open + in-company, meerdere locaties | €290–€1.270+ excl. btw | ISO-gecertificeerd maar generiek; geen integratie met procesautomatisering |
| **Voka** | "AI in de praktijk", AI Act, sector-workshops | Open (leden) | €255–€385 p.p. | Leden-organisatie; niet gericht op kleinste kmo's |
| **AI Learning.be** | Op maat dagtraining in-company, implementatietraject, AI Act-compliance | In-company | Niet gepubliceerd | Vendor-neutraal en praktijkgericht — directe concurrent in positionering |
| **VAIA (Vlaamse AI Academie)** | Sector-specifiek (bouw, food, retail, vastgoed, maakindustrie) | Gevarieerd, VLAIO-gesteund | Niet gepubliceerd | Sector-specifiek; niet voor alle kmo-types |

Bronnen: eigen webonderzoek 2026-06-12 op de respectieve websites.

### 6.2 Analyse: witte vlekken in het aanbod

Geen enkele van de bovenstaande aanbieders combineert:
1. Een korte, praktische AI-opleiding
2. met een directe link naar procesautomatisering (sprint)
3. voor de **kleinste kmo's in de Kempen** (buiten Gent/Antwerpen/Brussel)
4. met een **vaste prijs + resultaatsbelofte**

Cevora is gratis maar generiek en paritaire-commissie-gebonden. Syntra is campusgebonden.
SBM is breed maar duur voor de kleinste kmo's. VAIA is sector-specifiek. AI Learning.be is
de dichtstbijzijnde concurrent qua positionering, maar opereert zonder de sprint-koppeling.

### 6.3 Differentiatie van Auxilia

Auxilia's onderscheid is niet de opleiding op zich, maar de **combinatie**:

> *"Je medewerkers begrijpen AI én de volgende dag gebruiken ze het al in het proces dat we
> samen gebouwd hebben."*

Concrete differentiators:

| Differentiator | Auxilia | Concurrentie |
|---|---|---|
| Koppeling opleiding–automatisering | Ja (sprint = automatisering + opleiding) | Nee |
| Lokale aanwezigheid Kempen | Ja | Nee (of minimaal) |
| Vaste prijs + resultaatsbelofte | Ja | Nee |
| Materiaal op maat per bedrijfsproces | Ja (intake voor in-company) | Gedeeltelijk (SBM, AI Learning.be) |
| Instap via betaalde AI-analyse | Ja (uniek: analyse → rapport → opleiding/sprint) | Nee |
| Subsidiegids voor de klant | Voorbereid, nog niet actief (DV.O uitgesteld) | Soms |

---

## 7. Evaluatie van effectiviteit: meetpunten

### 7.1 Principe

Een opleiding die "werkte" moet aantoonbaar zijn voor de klant én bruikbaar als referentie.
Kirkpatrick's vier niveaus vormen het raamwerk:

| Niveau | Wat meten | Wanneer | Instrument |
|---|---|---|---|
| **1. Reactie** | Tevredenheid, relevantie, trainer | Einde sessie | Evaluatieformulier (ook auditverplicht) |
| **2. Leren** | Kennis en vaardigheid getest | Einde sessie (korte quiz of oefening) | 5-vragenquiz of terugkoppeling Module 4 |
| **3. Gedrag** | Gebruikt de deelnemer AI 30 dagen later? | 30 dagen na sessie | Kortmail met 3 vragen (zie §7.2) |
| **4. Resultaat** | Tijdwinst, kwaliteitsverbetering | 90 dagen na sessie | Optionele telefonische check (15 min) |

### 7.2 30-dagen-follow-up (verplicht element)

Elke deelnemer ontvangt 30 dagen na de sessie een e-mail met drie vragen:

1. Welke AI-taak uit je 30-dagen-actiekaart gebruik je nu echt? (open vraag)
2. Hoeveel tijd bespaar je daarmee per week? (vrij in te vullen)
3. Wat houdt je nog tegen om meer te doen met AI? (open vraag + 3 vaste opties)

De antwoorden worden:
- Gerapporteerd aan de klant (in-company: samenvatting naar zaakvoerder)
- Gebruikt als testimonial materiaal (met toestemming)
- Opgeslagen als bewijs van gedragsverandering (niveau 3 Kirkpatrick)

### 7.3 Bruikbaar als verkoopreferentie

De 30-dagen-data zijn het ruwe materiaal voor case studies:

> *"Na de dagcursus bij [bedrijfsnaam] meldden 7 van de 10 deelnemers dat ze AI wekelijks
> gebruiken; gemiddeld besparingen van 2,5 uur per week per persoon."*

Gebruik als testimonial op de website, in offertes en in de Kempen-community zodra de
eerste 3 bedrijven door de opleiding zijn.

---

## 8. Didactische valkuilen en hoe het ontwerp ze opvangt

### 8.1 Geïdentificeerde valkuilen bij AI-opleidingen voor niet-technische volwassenen

| Valkuil | Beschrijving | Hoe het ontwerp dit opvangt |
|---|---|---|
| **Angst en weerstand** | Medewerkers vrezen dat AI hun job bedreigt; worden defensief | Opening M1: expliciteer de angst actief (sticky-note oefening). Kadreer AI als hulpmiddel, niet als vervanger. Gebruik de term "jouw copiloot" |
| **Theorieparade** | Slides vol uitleg over hoe LLM's werken — irrelevant en demotiverend | Geen theorie in M1. Demo-eerste aanpak. Deelnemers zien direct output, pas daarna concept |
| **Overbelasting** | Te veel tools tegelijk (ChatGPT + Copilot + Gemini + Bard + …) | Focus op maximaal 2 tools per dag; consistent één tool doorheen de oefeningen |
| **Gebrek aan transfer** | Deelnemers doen het wel in de oefening maar niet daarna op het werk | 30-dagen-actiekaart (M4) + follow-up e-mail 30 dagen later |
| **Oververtrouwen in AI** | Deelnemers accepteren elke AI-output zonder te controleren | Fouten-challenge (M4) + vertrouwensladder + beslisregel "hoe hoger de impact, hoe meer je verifieert" |
| **Cognitieve overbelasting** | Te veel nieuwe concepten in te korte tijd | Maximaal 3 nieuwe concepten per module; herhaling via oefeningen niet via slides |
| **Privacyblindheid** | Deelnemers voeren bedrijfsgevoelige data in publieke AI-tools | GDPR-cheatsheet (M3) + expliciete "no-go zone" bespreking met concrete voorbeelden |
| **Trainer als alwetende AI-goeroe** | Deelnemers verwachten perfecte antwoorden; trainer verliest geloofwaardigheid bij fout | Trainer modelt actief twijfel en zelfcorrectie: "Kijk, dit klopt niet — dit is hoe je dat herkent" |

Bronnen voor de didactische principes: [SHRM — Engage employees in AI without triggering fear](https://www.shrm.org/enterprise-solutions/insights/how-to-engage-employees-ai-without-triggering-fear) (geraadpleegd 2026-06-12); [eLearning Industry — Learning Design in 2026](https://elearningindustry.com/envisioning-2026-where-ai-learns-fast-and-humans-learn-wise) (geraadpleegd 2026-06-12); [Experiential Learning for Corporate Training 2026 | iSEAZY](https://www.iseazy.com/blog/experiential-learning-online-training/) (geraadpleegd 2026-06-12)

### 8.2 Het Kolb-principe in dit ontwerp

Elke module volgt de cyclus van ervaringsgericht leren (Kolb, 1984):

1. **Concrete ervaring** — deelnemers werken met een echt AI-tool op een echte taak
2. **Reflectief observeren** — deelnemers bespreken wat ze zagen, wat fout liep, wat verraste
3. **Abstract conceptualiseren** — de trainer geeft een compacte naam/formule aan het patroon
4. **Actief experimenteren** — deelnemers passen het toe op hun eigen situatie en bewaren het resultaat

De oefeningen zijn zo gebouwd dat elke deelnemer iets **meeneemt naar het werk** (patroonkaart, promptsjabloon, GDPR-cheatsheet, 30-dagen-kaart). Dat is de transfergarantie.

---

## 9. Openstaande beslissingen voor Cedric

> Beslissingen die in rev. 1 nog open stonden maar nu **genomen zijn** (verwijderd):
> — "Cursussen als poot: ja of nee?" → Ja, derde poot (beslissing 2026-06-12).
> — "DV.O-registratie wanneer?" → Uitgesteld; geen kmo-portefeuille op korte termijn.
> — "AI-analyse als kerninstapproduct?" → Ja (beslissing 2026-06-12).

De volgende keuzes zijn **nog open** en beïnvloeden de uitvoering van dit hoofdstuk:

1. **Opleidingsluik sprint — apart factureren?**: wordt het opleidingsluik (3 uur) apart
   gefactureerd of zit het in de sprintprijs vervat? Op korte termijn geen subsidieargument,
   maar aparte facturatie vereenvoudigt een latere subsidieclaim en maakt de
   opleidingskost inzichtelijker voor de klant. ❓ Cedric beslist.

2. **Locatiepartner Kempen**: open workshops vereisen een zaal. Wil je samenwerken met een
   vaste partner (Voka-lokaal, gemeentehuis, co-working)? Heeft Auxilia (of een van de
   teamleden) toegang tot een geschikte ruimte?

3. **Rolverdeling opleiding**: uit `00-context.md` blijkt dat "Lien Vandereyt" het
   opleidingsprofiel draagt. Wie geeft de opleidingen in de praktijk? Kan dat bijberoep
   gecombineerd worden? Hoeveel uren per maand zijn beschikbaar?

4. **Prijsvastlegging**: de prijsranges hierboven zijn marktconform maar moeten bevestigd
   worden. In het bijzonder: is €395–€450 p.p. voor de open dagworkshop haalbaar in de
   Kempenmarkt, of is een lager instapbedrag nodig voor de lancering?

5. **Abonnementsformule**: wil je dit al in de eerste 6 maanden activeren, of pas later?
   Vraagt een platform (Zoom, opnameinfrastructuur) en consistente tijdsinvestering per maand.

6. **Taal van de opleiding**: de materialen zijn voor 100% Nederlands. Zijn er klanten waar
   ook Frans- of Engelstalige medewerkers aanwezig zijn? Zo ja, dit vraagt een aparte versie.

7. **Verhouding analyse-rapport en opleidingsaanbeveling**: in welke gevallen raadt het
   AI-analyserapport een in-company dagcursus aan versus een sprint-opleidingsluik? Moet
   er een beslisboom of standaardzin in het rapport komen? Dit raakt het domein van de
   sprint-ontwerper maar vraagt ook een gestandaardiseerde koppeling vanuit het
   opleidingsaanbod.

8. **Heroverwegen DV.O-registratie**: wanneer is het moment waarop losse opleidingen
   aantoonbaar verkopen en de registratie wél de moeite waard is? ❓ Cedric bepaalt de
   drempel (bv. "als we 5 betalende cursusklanten hebben, starten we de auditprocedure").
