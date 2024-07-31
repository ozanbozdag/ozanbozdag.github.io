---
#layout: archive
#title: "Teaching"
permalink: /teaching/
#author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

I teach undergraduate and graduate-level courses at Georgia Tech:

**•**	**Evolutionary Biology** (BIOS 3600 / BIOL 6600)

This course provides a comprehensive introduction to evolutionary biology for intermediate undergraduate and beginning graduate students. It aims to develop population thinking skills, teach interpretation of scientific literature, and explain how evolutionary forces shape biodiversity. Topics covered include the history of life, major evolutionary transitions, speciation, phylogenetics, natural and sexual selection, experimental evolution, genetics, genetic drift, genome evolution, and evo-devo. Students will gain a solid foundation in evolutionary theory and its modern applications.

Optional textbooks:

**•** Evolution by Carl Bergstrom and Lee Dugatkin  
**•** Evolutionary Analysis by Jon Herron and Scott Freeman


**•** **Communicating Biological Research** (BIOS 4460)

This course is designed to help students develop their oral and poster presentation skills. Students will learn how to effectively engage their audience when presenting scientific topics, as well as how to present and discuss their own research results critically. In addition, students will learn how to think critically and provide constructive feedback on their classmates' presentations. Although the course focuses on improving students' ability to give engaging talks on research projects, the skills they will develop are applicable to a wide range of future careers.

**•** **Microbiology Lab** (BIOS 3381)

This lab is designed to explore commonly used microbiological techniques, such as field sampling,
enumeration and cultivation of microorganisms, targeted enrichment and isolation techniques, determinations
of microbial growth, antibiotic resistance, antibacterial potential, DNA extraction, next generation sequencing,
and bioinformatic analyses.