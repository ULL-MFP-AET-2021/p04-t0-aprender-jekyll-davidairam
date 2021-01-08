---
layout: post
title: Primera clase de Tecnología
profesor: David Airam
link_github: https://github.com/davidairam
---

Hola a todos, mi nombre es {{ page.profesor }} y seré su profesor de Tecnología.

A lo largo de este curso de Tecnología vamos a estudiar los siguientes temas:

{% for tema in site.temas %}
  {%- if tema.visible -%}
    - {{ tema.name }}
  {%- endif %}
{% endfor %}

<br>
<h0>

Bla bla bla more content.

El veloz murciélago hindú comía feliz cardillo y kiwi. La cigüeña tocaba el saxofón detrás del palenque de paja.
<br><br>
No se olviden visitar
<a href="{{ page.link_github }}">mi página</a> de GitHub y mencionen en la siguiente clase un proyecto interesante que les haya gustado.
<br><br>
--FIN--