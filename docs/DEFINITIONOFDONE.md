# Definition of Done

De aanpassingen staan op de dev omgeving (<https://kiss-dev.commonground.nu/>) en voldoen aan alle acceptatiecriteria.

**De applicatie voldoet aan de ontwerpprincipes van Gebruiker Centraal.**
De eindgebruiker is betrokken is gedurende het hele project betrokken bij ontwerp en specificatie. De applicatie wordt regelmatig getest door de gebruikers.

**Code is gereviewd zijn door een andere developer.**
Er wordt ontwikkeld in feature branches en gedeployed vanaf de development branch. Zodoende is in GitHub inzichtelijk wie aan een story gewerkt heeft en wie een pull request approved heeft.

**Automatische tests**
Alle Automatische tests zijn uitgevoerd en geslaagd (zichtbaar als badges op de README)

**Unit Tests (Nieuwe unit tests worden toegevoegd naar inzicht van de developer.)**
Snyk (vulnerability en OWASP scanning)
Docker vulnerablity check
Better  Code Hub (code quality)
Aanwezigheid ongewenste variabelen (tokens, secrets etc.) (alleen indien we hier een tool voor kunnen vinden, anders schrappen we dit uit de DoD en wordt het eventueel een audit/review onderdeel)

**Handmatige tests**
Alle handmatige tests zijn uitgevoerd en geslaagd (afgevinkt en bij voorkeur een rapport toegevoegd aan de story)

**Functioneel testen.**
WCAG. wordt handmatig gecontroleerd m.b.v. lighthouse. De resultaten van deze test vindt u [hier](https://github.com/Klantinteractie-Servicesysteem/.github/blob/main/docs/WCAG-Lighthouse-Report-20221219.pdf).<br />
Pentests (frontend en backend) Wordt periodiek uitgevoerd (maandelijks). We maken de afspraak dat resultaten uit een vorige pentest bij de eerstvolgende story opgelost worden. De oplossing wordt echter pas gecontroleerd bij de volgende pentest.


**Documentatie voor contributors**: code voorzien in code documentatie, dit wordt bij de code review beoordeeld

**Documentatie voor eindgebruikers**: is geen onderdeel van het project?

**Documentatie voor implementatiepartners**: Changes.md is aangevuld met release notes aan de hand van symantic versioning en per release werken we een implementatie handleiding bij
De DoD is een waarborg voor (een deel van) de architectuurkaders
