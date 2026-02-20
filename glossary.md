---
layout: default
title: "Glossary"
permalink: /en/
---

# Glossary

**Please note the English section of the site is still under development.**

Faclair nan Gèidheal is a dictionary of Scottish Gaelic, Irish, and Manx LGBTQIA+ vocabulary collated by the Gaelic LGBTQIA+ news blog [An Gèidheal Ùr](https://angeidhealur.scot).

Below is an English list of every entry in the dictionary. Each one has Gaelic and English translations, the vast majority have Irish translations, but very few have Manx translations.

If you are aware of any missing words, particularly Manx words, I'd be very grateful if you could let me know via [email](mailto:fios@angeidhealur.scot) or [Bluesky](https://bsky.app/profile/angeidheal.scot).

{% for facal in site.faclair %}
   <p><a href="{{ site.baseurl }}{{ facal.url }}">{{ facal.beurla }}</a></p>
{% endfor %}