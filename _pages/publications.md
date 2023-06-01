---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## 2023
  * __NeuRex: A Case for Neural Rendering Acceleration__
    __Junseo Lee__, Kwanseok Choi, Jungi Lee, Seokwon Lee, Whangbo Joonho, Jaewoong Sim
    Proc. of the 50th International Symposium on Computer Architecture (ISCA), Orlando, FL, June 2023
