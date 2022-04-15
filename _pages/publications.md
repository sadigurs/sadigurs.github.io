---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Conferences
- **On the Sample Complexity of Privately Learning Axis-Aligned Rectangles** [NeurIPS 2021](https://nips.cc/)  
  Menachem Sadigurschi, [Uri Stemmer](https://www.uri.co.il/)  
  [Arxiv](https://arxiv.org/abs/2107.11526)  | [NeurIPS page](https://neurips.cc/virtual/2021/poster/27837)
- **Sample Compression for Real-Valued Learners** [ALT 2019](http://alt2019.algorithmiclearningtheory.org/)  
  [Steve Hanneke](http://www.stevehanneke.com/), [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), Menachem Sadigurschi  
  [Arxiv](https://arxiv.org/abs/1805.08254) | [Lecture](https://www.youtube.com/watch?v=ueEvY4Ws0l4)  

### Preprints
- **Adaptive Data Analysis with Correlated Observations**  
  [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), Menachem Sadigurschi, [Uri Stemmer](https://www.uri.co.il/)    
  [Arxiv](https://arxiv.org/abs/2201.08704)  
- **Agnostic Sample Compression for Linear Regression**  
  [Steve Hanneke](http://www.stevehanneke.com/), [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), Menachem Sadigurschi  
  [Arxiv](https://arxiv.org/abs/1810.01864)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
