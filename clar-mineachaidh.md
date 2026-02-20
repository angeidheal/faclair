---
layout: default
title: "Clàr-mìneachaidh"
permalink: /clar-mineachaidh/
---

<p>Seo liosta de na faclan uile a tha san fhaclair, air an òrdachadh a rèir litir. Cliog air facal sam bith airson tuilleadh fiosrachaidh mu dheidhinn.</p>

{% for facal in site.faclair %}
   <p><a href="{{ site.baseurl }}{{ facal.url }}">{{ facal.title }}</a></p>
{% endfor %}