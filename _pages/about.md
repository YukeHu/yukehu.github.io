---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html

---

I am a postdoctoral researcher at [King Abdullah University of Science and Technology (KAUST)](https://www.kaust.edu.sa/), working with [Prof. Di Wang](https://shao3wangdi.github.io/).
I completed my Ph.D. at Zhejiang University under the guidance of [Prof. Zhan Qin](https://person.zju.edu.cn/en/zhanqin). From May 2024 to January 2025, I was a visiting student at the CISPA Helmholtz Center for Information Security, where I worked under the supervision of [Dr. Yang Zhang](https://yangzhangalmo.github.io/).

## Research Interests

My research interests are trustworthy large models and data privacy and security. Recent work covers privacy defenses for large models, differentially private training and inference, and machine unlearning.

## Selected Publications

<div class="pubs">
{% for p in site.data.publications %}{% if p.selected %}{% include publication.html p=p %}{% endif %}{% endfor %}
</div>

\* equal contribution, † corresponding author. See the [full list of publications](/publications/).

## News

- **Sep 2026** Our paper “Ask in the Crowd: Differentially Private LLM Inference via Dummy-Augmented Shuffling” was accepted to NeurIPS 2026.
- **Sep 2026** Our paper “Towards Mitigating Excessive Forgetting in LLM Unlearning via Entanglement-Guidance with Proxy Constraint” was accepted to TDSC.
- **Apr 2026** I joined KAUST as a postdoctoral researcher.
- **Mar 2026** Our paper “Differentially Private Zeroth-Order Methods for Scalable Large Language Model Fine-Tuning” was accepted to TIFS.
- **Jan 2026** Our paper “LFS: A Locally Private Framework for Degree Statistic Estimation with Laplace Mechanism” was accepted to TIFS.
- **Dec 2025** Our paper “Shadow in the Cache: Unveiling and Mitigating Privacy Risks of KV-cache in LLM Inference” was accepted to NDSS 2026.
- **Jun 2025** I defended my Ph.D. thesis at Zhejiang University.
{: .news}

<details markdown="1">
<summary markdown="span">Earlier news</summary>

- **Jan 2025** Our paper “Membership Inference Attacks Against Vision-Language Models” was accepted to USENIX Security 2025.
- **Dec 2024** Our paper “Privacy Risks of Federated Knowledge Graph Embedding: New Membership Inference Attacks and Personalized Differential Privacy Defense” was accepted to TDSC.
- **May 2024** I started visiting CISPA.
- **Apr 2024** Our paper “ERASER: Machine Unlearning in MLaaS via an Inference Serving-Aware Approach” was accepted to CCS 2024.
- **Jan 2023** Our paper “Quantifying and Defending against Privacy Threats on Federated Knowledge Graph Embedding” was accepted to WWW 2023 and selected as a spotlight paper.
- **Sep 2022** Our paper “OpBoost: A Vertical Federated Tree Boosting Framework Based on Order-Preserving Desensitization” was accepted to VLDB 2022.
{: .news}

</details>

## Service

- **Program committee** SaTML 2027, SaTML 2026
- **Conference reviewer** WWW 2027, NeurIPS 2026
- **Journal reviewer** IEEE TPAMI, IEEE TDSC, IEEE TIFS, ACM TOPS, IEEE TKDE, TMLR
{: .service}
