# Autores

{% for item in book.authors %}
Versión actualizada octubre de 2018


1. {{item.title}}: {{item.name}}

{% endfor %}

___

{% include "git+https://github.com/catedu/faq-aularagon.git/imagenes_creditos.md" %}