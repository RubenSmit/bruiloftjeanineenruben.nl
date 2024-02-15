---
title: Programma · Bruiloft Jeanine en Ruben · 27-29 | 08 | 2024
description: Drie dagen? Wat gaan jullie doen dan? Hier wat antwoorden op je vragen.
layout: default
---

{% capture card_content %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla semper, risus non auctor vestibulum, felis orci euismod
risus, id viverra tortor felis et lorem. Nunc nec est lorem. Pellentesque suscipit ligula quam, et ornare dui
consectetur eu. Duis lacinia dolor magna, id scelerisque libero fringilla at. Pellentesque sem odio, facilisis
consectetur quam ac, fermentum eleifend lacus. Nam vel sollicitudin nisi, efficitur congue libero. Integer libero
lectus, cursus eget purus id, finibus consequat purus. Nulla blandit maximus tortor, sed ultrices purus pretium vitae.
Phasellus at aliquet leo. Sed sed mauris bibendum, molestie magna id, accumsan urna. Aenean pulvinar leo et nisl tempor,
faucibus condimentum nunc auctor. Cras rhoncus faucibus augue, non vulputate arcu laoreet eu. 

{% include card_title.html title="Dinsdag 27 augustus" %}
{% capture dinsdag_items %}
{% include timeline_item.html time="14:00" content="Aankomst alles-gasten" %}
{% include timeline_item.html time="15:00" content="Koffie en Thee" %}
{% include timeline_item.html time="16:00" content="Burgerlijk huwelijk" %}
{% include timeline_item.html time="18:00" content="Diner" %}
{% include timeline_last_item.html time="21:00" content="Borrel en stukjes" last=true %}
{% endcapture %}
{% include timeline.html items=dinsdag_items %}

{% include card_title.html title="Woensdag 28 augustus" %}
{% capture woensdag_items %}
{% include timeline_item.html time="07:00 - 09:00" content="Ontbijt" %}
{% include timeline_item.html time="10:00" content="Klaarmaken locatie" %}
{% include timeline_item.html time="11:00" content="Inloop daggasten" %}
{% include timeline_item.html time="12:00" content="Lunch" %}
{% include timeline_item.html time="12:30" content="Groepsfoto's" %}
{% include timeline_item.html time="13:30" content="Inloop kerkgasten" %}
{% include timeline_item.html time="14:00" content="Kerkdienst" %}
{% include timeline_item.html time="16:00" content="Receptie" %}
{% include timeline_item.html time="17:45" content="Vertrek kerkgasten" %}
{% include timeline_item.html time="18:00" content="Diner" %}
{% include timeline_last_item.html time="21:00" content="Feest" %}
{% endcapture %}
{% include timeline.html items=woensdag_items %}

{% include card_title.html title="Donderdag 29 augustus" %}
{% capture donderdag_items %}
{% include timeline_item.html time="09:00 - 12:00" content="Brunch" %}
{% include timeline_last_item.html time="12:00" content="Opruimen" %}
{% endcapture %}
{% include timeline.html items=donderdag_items %}

{% endcapture %}

{% include card.html title="Programma" content=card_content %}
