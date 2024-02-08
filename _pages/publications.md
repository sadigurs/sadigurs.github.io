---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### Conferences
- **Relaxed Models for Adversarial Streaming: The Advice Model and the Bounded Interruptions Model**   
  Menachem Sadigurschi, [Uri Stemmer](https://www.uri.co.il/), [Moshe Shechner](https://www.shechner.com/)   
  [Arxiv](https://arxiv.org/abs/2301.09203) | *To appear at [ESA2023](https://algo-conference.org/2023/esa/)*   
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
- **Agnostic Sample Compression Schemes for Regression**   
  [Idan Attias](https://www.idanattias.com/), [Steve Hanneke](http://www.stevehanneke.com/), [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), Menachem Sadigurschi   
  [Arxiv](https://arxiv.org/abs/1810.01864)   
- **Differentially-Private Bayes Consistency**  
  [Olivier Bousquet](https://research.google/people/OlivierBousquet/), [Haim Kaplan](https://www.cs.tau.ac.il/~haimk/), [Aryeh Kontorovich](https://www.cs.bgu.ac.il/~karyeh/), [Yishay Mansour](https://www.tau.ac.il/~mansour/), [Shay Moran](https://www.cs.technion.ac.il/~shaymrn/), Menachem Sadigurschi, [Uri Stemmer](https://www.uri.co.il/)    
  [Arxiv](https://arxiv.org/abs/2212.04216)  

## Thesis - Ph.D.
[A Study of Privacy and Compression in Learning Theory](/files/phd_meni.pdf)

## Thesis - M.Sc.
[Compression-Schemes for Real-Valued Learners](/files/0main.pdf)  

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
