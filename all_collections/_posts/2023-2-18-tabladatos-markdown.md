---
layout: post
title: datos
date: 18-02-23
permalink: /data/
---
| NOMBRE            | GENERO       | EDAD|
{% for dato in site.data.datos %}
| {{ dato.valor1 }} | {{ dato.valor2 }} | {{ dato.valor3 }} |
{% endfor %}

# Tablas de datos a partir de un archivo .yml con Jekyll y Markdown :sunglasses: