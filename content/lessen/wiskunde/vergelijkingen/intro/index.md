---
title: "Wat is een vergelijking?"
date: 2019-01-07T23:20:25+01:00
weight: 1
draft: false
tags: ["vergelijkingen", "algebra"]
categories: ["wiskunde", "algebra"]
level: "2M"
course: "wiskunde"
topic: "algebra"
---
Een van de meest essentiële vaardigheden voor een uit-de-kluiten-gewassen wiskundige is het kunnen oplossen van **vergelijkingen**. Om te begrijpen *waarom* het oplossen van vergelijkingen zo belangrijk is, heb je best al wat kennis van [functies](../../functies/).

Kort gezegd zijn de belangrijkste toepassingen van vergelijkingen:

1. Het vinden van de [nulpunten](../../functies/nulpunten) van een functie;
2. Het vinden van de snijpunten van de [grafieken](../../functies/grafiek) van twee functies.

We zullen in een [latere les](../functies) het verband tussen functies en vergelijkingen iets uitgebreider bespreken.

## Hoe een vergelijking eruit ziet
Een vergelijking heeft meestal de vorm
$$(\ldots \text{een berekening met }x \ldots) = (\ldots \text{een andere berekening met }x \ldots)$$

Alles wat **links** van het gelijkheidsteken staat, noemen we **het linkerlid**. Alles wat **rechts** van het gelijkheidsteken staat, noemen we **het rechterlid**.

Enkele voorbeelden van vergelijkingen:
$$x + 6 = 2 - 3x$$
Maar het kan ook ingewikkelder zijn:
$$4x^2 - 3 = 2x^2 + 5$$
En zelfs:
$$\frac{\sin(2x) - \cos(-x)}{\sqrt{-x + 3}} = 6x + 1$$

Geen paniek als je van die laatste vergelijking niet veel begrijpt, het is maar om te tonen dat een vergelijking niet altijd in zo'n propere vorm zit als de eerste vergelijking.

## De onbekende $x$
De $x$ in de vergelijking noemen we de **onbekende**. In principe kan je eender welke letter gebruiken als onbekende, maar de gewoonte is om een $x$ te gebruiken.

Het kan ook zijn dat er *verschillende* onbekenden zijn in één vergelijking, bijvoorbeeld
$$x^2 - 2y + 6 = 5 - 3x + z$$
Waar we naast $x$ ook $y$ en $z$ als onbekende hebben. Zo'n vergelijking noemen we dan *een vergelijking in drie onbekenden*. Dit soort vergelijkingen komt later terug in het deel over [stelsels](../../stelsels).

## Oplossingsverzameling
De bedoeling van een vergelijking is meestal om te zoeken **welk(e) getal(len)** we in plaats van de onbekende(n) {{% mute "(meestal gewoon $x$)" %}} kunnen zetten **zodat de gelijkheid klopt**. Die getallen noemen we de *oplossingen* van de vergelijking.

Voor het eerste voorbeeld $\orange{x} + 6 = 2 - 3\orange{x}$, is er maar één getal waarvoor de 
gelijkheid klopt: $\orange{-1}$:
\begin{split}
\orange{-1} + 6 &= 2 - 3 \cdot (\orange{-1})\\\\\
5 &= 2 + 3\\\\\
5 &= 5
\end{split}

Als je de oplossing(en) in een [verzameling](../../verzamelingen) stopt, noemen we die verzameling de *oplossingsverzameling* van de vergelijking. We stellen de oplossingsverzameling meestal voor met de letter $V$.

De oplossingsverzameling $V$ voor het voorbeeld is dus:
$$V = \\{\orange{-1}\\}$$

## Samengevat
{{% attention "Vergelijking" %}}
Een vergelijking is iets van de vorm
$$\text{linkerlid} = \text{rechterlid}$$
Waarbij $\text{linkerlid}$ en $\text{rechterlid}$ een of meerdere **onbekenden** bevatten. Vaak is er maar één onbekende, namelijk $x$.
{{% /attention %}}

{{% attention "Oplossingsverzameling" %}}
Een vergelijking is *opgelost* als je de waarden van de onbekenden vindt waarvoor de gelijkheid klopt. De *oplossingsverzameling* is de verzameling van die waarden.
{{% /attention %}}