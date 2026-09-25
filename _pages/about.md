---
permalink: /
title: "Anthony Swaminathan"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD candidate in Economics at Duke University. My primary research interest is macroeconomics, with secondary interests in labor, spatial, and behavioral economics.

**I will be on the 2026-2027 job market.**

{% assign jmp = site.publications | where: "category", "jmp" | first %}
{% if jmp %}
My job market paper is "{{ jmp.title }}."{% if jmp.draft %} You can find a link to the paper <a href="{{ jmp.draft }}">here</a>.{% endif %}

{% assign abstract = jmp.content | strip_html | strip %}
{% if abstract != "" %}<details class="home__abstract"><summary>Abstract</summary>{{ jmp.content }}</details>{% endif %}
{% endif %}

You can also access my CV [here](https://www.dropbox.com/scl/fi/3v1nz1jwbslmuv4kut9s4/Swaminathan-CV.pdf?rlkey=rfjxnybbsqrfuiktf96y7llsf&raw=1).

Contact information
------
<p>
Department of Economics<br>
Duke University<br>
213 Social Sciences, Room 230<br>
Durham, NC 27708
</p>

<p>
Email: <a href="mailto:anthony.swaminathan@duke.edu">anthony.swaminathan@duke.edu</a><br>
Phone: (530) 601-8485
</p>
