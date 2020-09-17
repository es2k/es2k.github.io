---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

<a href="{{author.googlescholar}}"><i class="ai ai-google-scholar-square ai-fw"></i> <span style="color:blue">Google Scholar</span></a>


## Conference and Journal Papers
Works in progress
*	**Broken Relationship of Mobile User Intentions and Permission Control of Shared System Resources**<br/>
	Hao Wu, Zheng Qin, Xuejin Tian, **Edward Sun**, Fengyuan Xu, Sheng Zhong<br/>
	In *IEEE Conference on Dependable and Secure Computing* (DSC 2019).

## Posters, Demos, and Workshop Papers
*	**Towards Universal Evaluation of Image Annotation Interfaces**<br/>
	Andrew M. Vernier, Jean Y. Song, **Edward Sun**, Allison Kench, Walter S. Lasecki<br/>
	In *Proceedings of the ACM Symposium on User Interface Software and Technology* (UIST 2019).<br/>
	<!--<span style="color:blue">[Paper](../files/corsica_UIST2019-poster.pdf)</span>-->


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
