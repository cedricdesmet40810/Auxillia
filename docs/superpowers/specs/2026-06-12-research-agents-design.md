# Design: Auxilia research-agent team

**Datum:** 2026-06-12
**Status:** goedgekeurd door Cedric

## Doel

Een herbruikbaar team van zes Claude Code-agentpersona's dat Cedric helpt het businessplan
voor Auxilia uit te werken: AI-automatisering, AI-implementatie en AI-opleiding voor Vlaamse
kmo's, gestart als zelfstandige in bijberoep. Elke persona bezit één hoofdstuk van het
businessplan en schrijft alle deliverables in het Nederlands.

## Context

- Auxilia bestaat al: landingspagina (one-pager, statisch HTML) met positionering rond een
  sprint-model (vaste prijs, vaste deadline), een tweekoppig team en het
  kmo-portefeuille-luik (sinds 1 feb 2026 enkel opleiding subsidieerbaar).
- Fase: beslissing genomen, plan nodig — geen ideevalidatie meer.
- Inzet: bijberoep eerst, met een pad naar voltijds zodra omzet dat bewijst.

## Bestandsstructuur

```
.claude/agents/
  marktonderzoeker.md
  financieel-planner.md
  opleidingsontwerper.md
  groeistrateeg.md
  subsidie-specialist.md
  businessplan-redacteur.md
business-plan/
  00-context.md               ← gedeelde feiten over Auxilia; agents lezen dit eerst
  01-markt.md                 ← eigendom van marktonderzoeker
  02-aanbod-opleidingen.md    ← opleidingsontwerper
  03-go-to-market.md          ← groeistrateeg
  04-financieel-plan.md       ← financieel-planner
  05-subsidies-compliance.md  ← subsidie-specialist
  businessplan.md             ← synthese door businessplan-redacteur
```

## De zes persona's

| Agent | Hoofdstuk | Domein |
|---|---|---|
| marktonderzoeker | 01-markt.md | Concurrentie, prijzen in de markt, sectoren met de meeste pijn, vraag naar AI-opleiding bij Vlaamse kmo's |
| opleidingsontwerper | 02-aanbod-opleidingen.md | Curriculum, formats (in-company vs. open workshops), eisen van kmo-portefeuille-auditors aan cursusmateriaal |
| groeistrateeg | 03-go-to-market.md | Eerste 10 klanten lokaal, LinkedIn/netwerkstrategie, partnerships (boekhouders, Voka, UNIZO) |
| financieel-planner | 04-financieel-plan.md | Prijszetting sprints & opleidingen, break-even in bijberoep, sociale bijdragen/btw, moment om voltijds te gaan |
| subsidie-specialist | 05-subsidies-compliance.md | kmo-portefeuille DV.O-registratie, VLAIO-audit, regelwijzigingen sinds feb 2026, GDPR/AI Act-basis voor klanten |
| businessplan-redacteur | businessplan.md | Synthese van de hoofdstukken; benoemt hiaten en tegenstrijdigheden als actiepunten in plaats van ze weg te schrijven |

## Agentbestand-formaat

Standaard Claude Code custom-agent-formaat per bestand:

- **Frontmatter:** `name`, `description` (zo geformuleerd dat automatische delegatie werkt
  bij een passende vraag), `tools` beperkt tot wat de rol nodig heeft:
  - Onderzoekende rollen (alle behalve redacteur): websearch/webfetch + lees/schrijf-tools.
  - Redacteur: enkel lees/schrijf-tools — hij synthetiseert, hij onderzoekt niet.
- **Body (Nederlands):**
  1. Persona en expertise.
  2. Het hoofdstukbestand dat de agent bezit.
  3. Verplichting om **altijd eerst `business-plan/00-context.md` te lezen**.
  4. Outputconventies: Nederlands; bronnen met URL en datum; concrete cijfers boven vage
     beweringen; hoofdstuk bijwerken in plaats van overschrijven zonder reden.
  5. 5–10 staande onderzoeksvragen voor het domein, zodat ook een vage prompt
     ("werk je hoofdstuk bij") nuttig werk oplevert.

## Gedeeld contextbestand (`00-context.md`)

De hoeksteen. Bevat:

- Wie: Cedric De Smet, zelfstandige in bijberoep; tweekoppig team volgens de site.
- Positionering: sprint-model, vaste prijs, opleiding vaak subsidieerbaar via
  kmo-portefeuille; doelregio Vlaanderen (lokaal starten).
- Een sectie **Beslissingen** die groeit naarmate keuzes vallen, zodat agents consistent
  blijven met genomen beslissingen in plaats van ze opnieuw ter discussie te stellen.
- Vooraf ingevuld vanuit de landingspagina; open vragen expliciet gemarkeerd zodat Cedric
  ze kan aanvullen.

## Werkwijze (gebruik)

1. Stel een vraag rechtstreeks aan een agent ("vraag de marktonderzoeker wat concurrenten
   vragen voor een AI-workshop") of laat meerdere agents parallel lopen.
2. Elke agent werkt zijn eigen hoofdstuk bij.
3. Wanneer hoofdstukken vers zijn, compileert de redacteur `businessplan.md` en lijst
   hiaten/tegenstrijdigheden op als actiepunten.

## Buiten scope

- Geen code, geen tests — alles is markdown.
- Geen wijzigingen aan de bestaande landingspagina.
- Geen automatische planning/cron; agents draaien op aanvraag.

## Verificatie

- Bestanden nalezen op consistentie met dit ontwerp.
- Rooktest: één agent aanroepen en controleren dat hij `00-context.md` leest en zijn
  hoofdstuk correct bijwerkt.
