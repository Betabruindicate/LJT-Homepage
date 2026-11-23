---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present.  
  HKUST NLP Group. Supervisor: Professor Junxian He. Recorded status: first-year Ph.D. candidate.
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024. Graduated in June 2024.  
  Professor Junxian He previously advised Junteng Liu during undergraduate studies at SJTU.

## Research Experience

- **Ph.D. research in Computer Science**, HKUST NLP Group, 2024–Present. Supervisor: Professor Junxian He.
- **Research Intern**, MINIMAX, February 2025–Present.
- **Research Intern**, Tencent WXG, June 2024–September 2024. Advisor: Zifei Shan.
- **Research Intern**, Shanghai AI Lab, June 2023–December 2023. Advisor: Prof. Yu Cheng.

## Honors and Awards

- **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University.

## Skills and Research Areas

- Natural language processing and machine learning.
- LLM reasoning and reinforcement learning.
- Hallucination in vision-language models.
- LLM truthfulness and interpretability.
- Verifiable reasoning data synthesis for logical reasoning.
- Chart understanding and vision-language perception analysis.
- Inner-representation analysis for hallucination mitigation.
- Foundation-model evaluation and parameter-efficient modules.

## Publications

{% assign cv_publications = site.publications | sort: "order" %}
<ol class="cv-publication-list">
{% for post in cv_publications %}
  <li>
    <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a><br />
    {{ post.authors }}.<br />
    <em>{{ post.venue }}</em>{% if post.role %} — {{ post.role }}{% endif %}{% if post.code_note %}<br />{{ post.code_note }}{% endif %}
  </li>
{% endfor %}
</ol>

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://x.com/junteng88716710)
