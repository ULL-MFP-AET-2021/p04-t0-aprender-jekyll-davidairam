---
layout: page
title: Prácticas
permalink: /practs/
---

{% for tarea in site.tareas %}
  {% if tarea.visible %}
    {{ tarea.my_order }}. {{ tarea.name }}
  {% endif %}
{%- endfor %}
