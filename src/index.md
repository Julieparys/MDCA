---
layout: default
name: home
title: Manx Digital Currency Association
banner: Home
---

###What is digital or cryptocurrency? Your questions answered

{% include learnMore.html %}

##Building the digital economy in the Isle of Man

The [Manx Digital Currency Association][1] was formed to promote all aspects of both existing and emerging digital currency and its related services.

Our [members][2] encompass a wide variety of business sectors associated with [digital currency][3] from frontline operators to service providers. We have an excellent relationship with the [Isle of Man Government][4] and its financial regulators.

---

## Latest News

{% assign post = site.posts.first %}
<h4><a href="{{ post.url }}">{{ post.date | date_to_string }} - {{ post.title }}</a></h4>
{{ post.excerpt }}
<a href="{{ post.url }}">&raquo; Read more</a>

[1]: /about-us/
[2]: /members/
[3]: /digital-currency/
[4]: http://www.gov.im/