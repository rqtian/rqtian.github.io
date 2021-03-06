---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- <span style="color:gold">[CGO'19]</span> -->

**[Under Submission]** **Ruiqin Tian**, Luanzheng Guo, Jiajia Li, Bin Ren, Gokcen Kestor. A High-Performance Sparse Tensor Algebra Compiler in Multi-Level IR. [Arxiv](https://arxiv.org/abs/2102.05187).

**[WHPC'2020]** **Ruiqin Tian**, Jiajia Li, Bin Ren, Gokcen Kestor. High-Performance Sparse Tensor Algebra Compiler. The 11th International Women in High Performance Computing Workshop (WHPC), in conjunction with ACM/IEEE International Conference for High-Performance Computing, Networking, Storage, and Analysis (SC). 2020. (Poster) 

**[LCPC'2020]** Erdal Mutlu, **Ruiqin Tian**, Bin Ren, Sriram Krishnamoorthy, Roberto Gioiosa, Jacques Pienaar and Gokcen Kestor. COMET: A Domain-Specific Compilation of High-Performance Computational Chemistry. The 33rd Workshop on Languages and Compilers for Parallel Computing (LCPC), October, 2020. [Arxiv](https://arxiv.org/abs/2102.06827)(Full paper)

**[ASE'2020]** Hongyu Liu\*, **Ruiqin Tian**\*, Bin Ren, and Tongping Liu (*equal contribution). [Prober: Practically Defending Overflows with Page Protection](https://ieeexplore.ieee.org/document/9286077). The 35th IEEE/ACM International Conference on Automated Software Engineering (ASE), September, 2020. (Acceptance Rate: 93/414 = 22.5%).

**[CGO'19]** **Ruiqin Tian**\*, Junqiao Qiu\*, Zhijia Zhao, Xu Liu, Bin Ren (\* co-primary). [Transforming Query Sequences for High-Throughput B+ Tree Processing on Many-core Processors](https://ieeexplore.ieee.org/document/8661166). The 2019 International Symposium on Code Generation and Optimization (CGO), February, 2019. (Acceptance Rate: 21/69 = 31%)

**[JOCA'15]** **Ruiqin Tian**, Jinzhao Wu, Ding Tang. [Design and implementation of light-weight rules engine on IoT gateway](http://www.joca.cn/EN/10.11772/j.issn.1001-9081.2015.04.1035). Journal of Computer Applications, 2015, 35(4): 1035-1039.

{% if author.googlescholar %}
   
{% endif %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
