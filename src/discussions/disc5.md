---
title: Lijst zonder bullets
tags: 1.3.1
label: failed, lijsten
permalink: false
github: https://github.com/WCAG-Audit-Discussions/NL-BE/issues/5
---

Stel je hebt iets wat duidelijk een lijst is van verschillende soorten van dezelfde soort data (een lijst van personen of adressen of links naar websites over hetzelfde thema). Maar er staan geen bullets voor.

Dus in plaats van

appels\
peren\
aardbeien

staat er

appels\
peren\
aardbeien

Als dit niet aangegeven is met een lijst element (zoals bijvoorbeeld een ul element in HTML) faalt dit dan SC 1.3.1?

#### Conclusie
Lijsten zonder bullets hebben alsnog de vormgeving van een lijst en moet ook softwarematig de lijst aangegeven zijn als lijst:

appels\
peren\
aardbeien

Dus dit bovenstaande voorbeeld faalt SC 1.3.1 als de lijst niet is aangegeven als lijst aangezien de vormgeving wel communiceert dat het hier om lijst elementen gaat maar dit niet bepaald kan worden door software en het niet duidelijk gemaakt wordt met behulp van tekst.
