---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.googlescholar %}
  <i class="ai ai-google-scholar-square ai-fw"></i> You can find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Works in Progress
*	**Document to Slide: Automatic Slideshow Generation**  
	IBM Research
*	**3D Prostate Cancer Lesion Detection**  
	Michigan Medicine

## Conference and Journal Papers
*	**EMO: real-time emotion recognition from single-eye images for resource-constrained eyewear devices**  
	Hao Wu, Jinghao Feng, Xuejin Tian, **Edward Sun**, Yunxin Liu, Bo Dong, Fengyuan Xu, Sheng Zhong  
	In *Proceedings of the 18th International Conference on Mobile Systems, Applications, and Services* (MobiSys 2020).
*	**Broken Relationship of Mobile User Intentions and Permission Control of Shared System Resources**<br/>
	Hao Wu, Zheng Qin, Xuejin Tian, **Edward Sun**, Fengyuan Xu, Sheng Zhong<br/>
	In *IEEE Conference on Dependable and Secure Computing* (DSC 2019).

## Posters, Demos, and Workshop Papers
*	**Towards Universal Evaluation of Image Annotation Interfaces**<br/>
	Andrew M. Vernier, Jean Y. Song, **Edward Sun**, Allison Kench, Walter S. Lasecki<br/>
	In *Proceedings of the ACM Symposium on User Interface Software and Technology* (UIST 2019).<br/>
	<!--<span style="color:blue">[Paper](../files/corsica_UIST2019-poster.pdf)</span>-->


{% include base_path %}
