---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Conferences
- **Adaptive Data Analysis with Correlated Observations** [ICML 2022](https://icml.cc/)  
  [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), Menachem Sadigurschi, [Uri Stemmer](https://www.uri.co.il/)    
  [Arxiv](https://arxiv.org/abs/2201.08704) | [ICML page](https://icml.cc/virtual/2022/spotlight/16034) | [Lecture](https://www.youtube.com/watch?v=10OUHwYU8cQ)  
- **On the Sample Complexity of Privately Learning Axis-Aligned Rectangles** [NeurIPS 2021](https://nips.cc/)  
  Menachem Sadigurschi, [Uri Stemmer](https://www.uri.co.il/)  
  [Arxiv](https://arxiv.org/abs/2107.11526)  | [NeurIPS page](https://neurips.cc/virtual/2021/poster/27837)
- **Sample Compression for Real-Valued Learners** [ALT 2019](http://alt2019.algorithmiclearningtheory.org/)  
  [Steve Hanneke](http://www.stevehanneke.com/), [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), Menachem Sadigurschi  
  [Arxiv](https://arxiv.org/abs/1805.08254) | [Lecture](https://www.youtube.com/watch?v=ueEvY4Ws0l4)  

### Preprints
- **Agnostic Sample Compression for Linear Regression**  
  [Steve Hanneke](http://www.stevehanneke.com/), [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), Menachem Sadigurschi  
  [Arxiv](https://arxiv.org/abs/1810.01864)

## Thesis - M.Sc.
[Compression-Schemes for Real-Valued Learners](/files/0main.pdf)  

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
