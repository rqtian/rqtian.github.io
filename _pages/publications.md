---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- <span style="color:gold">[CGO'19]</span> -->

**[CGO'19]** **Ruiqin Tian**\*, Junqiao Qiu\*, Zhijia Zhao, Xu Liu, Bin Ren (\* co-primary). Transforming Query Sequences for High-Throughput B+ Tree Processing on Many-core Processors. The 2019 International Symposium on Code Generation and Optimization (CGO), February, 2019. (Acceptance Rate: 21/69 = 31%)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
