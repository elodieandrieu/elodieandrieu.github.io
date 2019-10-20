---
layout: archive
permalink: /publications/
author_profile: true

---
### Publications 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!--- Publications --->
<!--- ------ --->

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Work in progress
<!--- Working Papers --->
<!--- ----- --->------

<!--- {% for post in site.working_papers reversed %} --->
<!--- {% include archive-single.html %} --->  
<!--- {% endfor %} --->

### Pre-doctoral publications

**[Occupational transitions: the cost of moving to a “safe haven”](https://www.oecd-ilibrary.org/docserver/6d3f9bff-en.pdf?expires=1571586413&id=id&accname=guest&checksum=421C4BF31745F1896B0D5DD9B0574ECA)** (with S. Jamet, L. Marcolin and M. Squicciarini)

*OECD Science, Technology and Industry Policy Papers, 2019* - https://doi.org/10.1787/6d3f9bff-en
