---
layout: archive
title: "Join us"
permalink: /join-us/
author_profile: true
---

<img src='/images/members.jpeg' style='height: 400px;'>

Our lab has two tracks:
- Algorithm track: [Software development](../research/algorithm)
- Bioinformatic track: [Phylogenetic analysis](../research/bioinformatic)

Not all positions are available for both tracks!

You can also check [our lab culture](../posts/2025/02/culture).

<ul>
{% include base_path %}

{% for post in site.join-us %}
  {% include archive-single.html %}
{% endfor %}
</ul>