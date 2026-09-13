---
permalink: /
title: "Anthony Swaminathan"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD candidate in Economics at Duke University. My primary research interest is macroeconomics, with secondary interests in labor and spatial economics.

**I will be on the 2026-2027 job market.**

{% assign jmp = site.publications | where: "note", "Job Market Paper" | first %}
{% if jmp %}
<div class="entry entry--featured">
<p class="entry__label">Job Market Paper</p>
<p class="entry__title">{% if jmp.paperurl %}<a href="{{ jmp.paperurl }}">{{ jmp.title }}</a>{% else %}{{ jmp.title }}{% endif %}</p>
{% assign abstract = jmp.content | strip_html | strip %}
{% if abstract != "" %}<details><summary>Abstract</summary>{{ jmp.content }}</details>{% endif %}
</div>
{% endif %}

You can find my CV [here](https://www.dropbox.com/scl/fi/3v1nz1jwbslmuv4kut9s4/Swaminathan-CV.pdf?rlkey=rfjxnybbsqrfuiktf96y7llsf&raw=1).

Contact information
------
[anthony.swaminathan@duke.edu](mailto:anthony.swaminathan@duke.edu)
