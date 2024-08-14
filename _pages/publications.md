---
layout: archive
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

1. A. Kumar, T. Ghosal, **S. Bhattacharjee** and A. Ekbal. "Towards automated meta-review generation via an NLP/ML pipeline in different stages of the scholarly peer review process". IJDL 2023. [[link]](https://link.springer.com/article/10.1007/s00799-023-00359-0)
2. A. Kumar, T. Ghosal, **S. Bhattacharjee** and A. Ekbal. "Investigations on Meta Review Generation from Peer Review Texts Leveraging Relevant Sub-tasks in the Peer Review Pipeline". TPDL 2022. [[link]](https://link.springer.com/chapter/10.1007/978-3-031-16802-4_17)
3. T. Ghosal, V. Edithal, T. Saikh, **S. Bhattacharjee**, A. Ekbal and P. Bhattacharyya. "Novelty Detection in Community Question Answering Forums". PACLIC 2022. [[pdf]](https://aclanthology.org/2022.paclic-1.58.pdf)
4. **S. Bhattacharjee**, K. Shinde, T. Ghosal and A. Ekbal. "A Multi-Task Learning Approach for Summarization of Dialogues". INLG 2022. [[pdf]](https://aclanthology.org/2022.inlg-genchal.16.pdf)
5. T. Ghosal, S. K. Das and **S. Bhattacharjee**, “Sentiment analysis on বাংলা রাশিফল (bengali horoscope) corpus”. INDICON 2015. [[link]](https://ieeexplore.ieee.org/abstract/document/7443551)
6. **S. Bhattacharjee**, A. Das, U. Bhattacharya, S. K. Parui and S. Roy, “Sentiment analysis using cosine similarity measure”. ReTIS 2015. [[link]](https://ieeexplore.ieee.org/abstract/document/7232847)
