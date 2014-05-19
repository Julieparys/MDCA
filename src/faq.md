---
layout: default
name: faq
title: Frequently Asked Questions - Digital Currency
permalink: digital-currency/faq/
color: blue
banner: DigitalCurrency
---

#Frequently Asked Questions

{% for faq in site.data.faq %}
####{{ faq.question }} 
<span class="glyphicon glyphicon-hand-right"></span> *{{ faq.answer }}*
{% endfor %}
