---
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="pubs">
{% assign years = site.data.publications | group_by: "year" %}
{% for y in years %}
<h2 id="{{ y.name }}">{{ y.name }}</h2>
{% for p in y.items %}{% include publication.html p=p %}{% endfor %}
{% endfor %}
</div>

\* equal contribution, † corresponding author
