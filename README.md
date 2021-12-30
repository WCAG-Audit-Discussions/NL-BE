# WCAG Audit Discussies in Nederland en Vlaanderen
Deze GitHub repository bevat Nederlandstalige discussies over hoe WCAG en de succescriteria te interpreteren en toe te passen.
Iedereen kan een probleem of vraag voorleggen door een [issue te openen](https://github.com/WCAG-Audit-Discussions/NL-BE/issues).

De uitkomst met een samenvatting van de discussie wordt daarna vastgelegd in de GitHub pages van deze repository:
GitHub pages: [WCAG Audit Discussion in Nederland en Vlaanderen](https://wcag-audit-discussions.github.io/NL-BE/)
De uitkomst wordt per succescriterium uitgeschreven en gelabeld:
- failed
- passes
- unclear

Het doel is om discussies vast te leggen en naar verwijzen bij onderzoeken en audits.
Iedereen is vrij om issues te openen en mee te discussiëren.

## Discussies
Deze omgeving is voor discussie over het interpreteren van de WCAG success criteria.
- Hoe interpreteer je de succescriteria van WCAG bij audits en consultancy?
- Wat zijn uitzonderingen?
- Hoe pas je de regels toe voor bijzondere constructies die je bij audits of reviews tegenkomt?

Heb je vragen of opmerkingen over WCAG zelf, dan is dit niet de goede plek.

## Code of conduct
We zijn lief en respectvol voor elkaar en voor elkaars mening.

## Beheerders
- [Rian Rietveld](https://github.com/rianrietveld) van Level Level
- [Brian Bors](https://github.com/ShadowBB) van Stichting Accessibility
- [Jules Ernst](https://github.com/julezrulez) van 200OK
- [Hidde de Vries](https://github.com/hidde) van Hidde de Vries
- [Marjon Bakker](https://github.com/MarjonBakker) van Firm Ground
- [Ronny Hendirks](https://github.com/Aircl0wn) van Toegankelijk Online

## Opzet GitHub pages

In Principe onderhouden de beheerders de GitHub Pages.
De pagina’s zijn gemaakt en worden bijgehouden met de [NPM module Eleventy](https://www.11ty.dev/docs/getting-started/). Voor een local install heb je [node.js](https://nodejs.org/en/) versie 10 of hoger nodig.

Stappen:
- clone deze repository op een voor jou geschikte plek
- open een terminal
- ga de directory van clone binnen: `cd NL-BE`
- draai Eleventy: `npx @11ty/eleventy --serve`

Er start dan een lokale webserver op met de GitHub pages http://localhost:8080

Wil je discussies wijzigen of toevoegen?
- maak je wijzigingen in de `NL-BE/src/` directory
- de files met de success criteria staan in `src/sc/` bijvoorbeeld: `Succescriterium-1-1-1-Niet-tekstuele-content.md`
- draai in de terminal, in de `NL-BE/` directory, `npx @11ty/eleventy --serve`.

Een van de beheerders doet een review van je pull request en beslist of een PR wordt gemerged en zo opgenomen bij de uitkomsten van de discussies.
