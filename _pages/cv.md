---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Statistics & Operations Research - Polytechnic University of Catalonia, 2019
* B.S. in Economics - Technical University of Loja, 2011
* B.S. in Accounting & Auditing - Central University of Ecuador, 2024

Work experience
======
* 2015 - Present: External Consultant
* Feb 2023 - Dec 2023: Research Analyst - Escuela Politécnica Nacional, Quito
* Jul 2021 - Apr 2022: Data Consultant - Ministerio de Turismo, Quito
* Jul 2020 - Mar 2022: Production Analyst - Fosforera Ecuatoriana S.A., Quito
* Aug 2027 - Jun 2020: External Consultant - Freelance, Barcelona
* Sep 2014 - Jul 2017: Tax Analyst - Procesadora Nacional de Alimentos C.A., Quito
* Nov 2011 - Aug 2014: Project Specialist - Freelance, Quito
  
Skills
======
* Programming Languages
  * Python
  * R
  * JavaScript
  * SAS
  * SQL
  * Julia

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
