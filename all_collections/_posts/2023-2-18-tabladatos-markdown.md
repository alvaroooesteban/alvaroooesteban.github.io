---
layout: post
title: datos
date: 18-02-23
permalink: /data/
---
| NOMBRE            | ASIGNATURAS       | OPINION |
{% for dato in site.data.datos %}
| {{ dato.valor1 }} | {{ dato.valor2 }} | {{ dato.valor3 }} |
{% endfor %}
