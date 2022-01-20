---
title: Dikgedrukte koppen per lijstitem
tags: 1.3.1
label: failed, markup
status: open
permalink: false
github: https://github.com/WCAG-Audit-Discussions/NL-BE/issues/3
---

Stel je hebt een lijst met lijstitems er in.

De lijst is goed aangegeven met een lijst rol en lijstitem rollen (bijvoorbeeld in HTML met ul element en li element), maar de content van elk lijstitem begint met een dikgedrukte term (bijvoorbeeld met CSS) en een linebreak.

- **Appels**<br />
Apples zijn rode of groene vruchten die aan bomen hangen.
- **Peren**<br />
Peren zijn ook vruchten die aan bomen hangen maar hebben een andere vorm.
- **Aardappels**<br />
Aardappels zijn geen vruchten en hangen niet aan bomen, ondanks hun verwarrende naam.

#### Conclusie
Dit wordt afgekeurd onder 1.3.1 aangezien er een relatie is aangegeven met behulp van vormgeving die niet door software bepaald kan worden.

Hier komt een stukje HTML

```html
<h2>Appels</h2>
<p>Apples zijn <a href="some-url">rode</a> of groene vruchten die aan bomen hangen.</p>
```

Stukje CSS
```css
.extra {
	font-weight: bold;
}
```
