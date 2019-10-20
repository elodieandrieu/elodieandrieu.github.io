---
layout: archive
permalink: /publications/
author_profile: true

---
## Publications 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!--- Publications --->
<!--- ------ --->

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in progress
<!--- Working Papers --->
<!--- ----- --->------

<!--- {% for post in site.working_papers reversed %} --->
<!--- {% include archive-single.html %} --->  
<!--- {% endfor %} --->

## Pre-doctoral publications

**Occupational transitions: the cost of moving to a “safe haven”** (with S. Jamet, L. Marcolin and M. Squicciarini)

*OECD Science, Technology and Industry Policy Papers* - 
