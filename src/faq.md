---
layout: default
name: faq
title: Frequently Asked Questions - Digital Currency
permalink: digital-currency/faq/
color: blue
banner: DigitalCurrency
---

<a name="top"></a>

#Frequently Asked Questions

Courtesy of [digitalcurrencyassociation.org.uk](http://www.digitalcurrencyassociation.org.uk/digital-currency-101).

<hr>

{% comment %}Quick Access List{% endcomment %}
<div class="row">
{% for faq in site.data.faq-uk %}

{% if faq.answer == "<!-- INLINE FAQS -->" %}
<div class="col col-md-6">
	<a href="#{{ faq.section }}">{{ faq.question }}</a>
</div>
{% endif %}
{% endfor %}
</div>

{% comment %}Main FAQ List{% endcomment %}
{% for faq in site.data.faq-uk %}
{% if faq.answer == "<!-- INLINE FAQS -->" %}
<hr>
<span class="glyphicon glyphicon-arrow-up"><a href="#top">top</a></span>
<a name="{{ faq.section }}"><h2>{{ faq.question }}</h2></a>
{% else %}
####{{ faq.question }}
<span class="glyphicon glyphicon-hand-right"></span>
<p class="well answer">*{{ faq.answer }}*</p>
{% endif %}
{% endfor %}
