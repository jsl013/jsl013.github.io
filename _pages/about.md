---
permalink: /
#title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
#excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

# About me
I am a MS student in snu-comparch lab at [SNU ECE](https://ee.snu.ac.kr),
Korea.  My research interests are in computer architecture, memory system, and
the architectural support for emerging workloads.

<a name="pubs"></a>
# Publications

{% include fmt-pub.html %}
