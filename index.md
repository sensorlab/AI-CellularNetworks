---
layout: page
title: "AI/ML Integration in 5G and Beyond"
subtitle: "Architecture and Prototypes"
use-site-title: true
---

<div class="venue" style="font-size: 24px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  <span style="font-size: 23px; font-weight: 300;">
    <a target="_blank" href="docs/slides.pdf">[Slides]</a>
  </span>
</div>

## Authors

<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <!-- <br> 
  <div class="row"> -->
  <div class="row">
    {% for p in site.presenters.data %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.presenters.data %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=8%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

---

## About the Tutorial

Machine Learning (ML) and Artificial Intelligence (AI) concepts are gradually being integrated in modern 3GPP standardized cellular networks. The process is initiated by introducing AI/ML functions in the 5G core network (5G CN) and from there, it is expanding towards AI-enabled 5G radio access network (RAN). AI/ML is currently at the early stage of design within 3GPP standardisation and many pathways for its impact are still open. In this talk, we present an overview of AI/ML integration in 5G and Beyond. Following the 3GPP perspective, we start from 5G CN and move towards 5G RAN, focusing on AI/ML impact on 5G and B5G physical layer design. We also cover complementary work done by Open RAN (O-RAN) Alliance. The tutorial is extended with demonstration of several use cases and applications of AI/ML integration in 5G/B5G.

### Topics:
-	Integration of AI/ML in 5G Core Network
-	Integration of AI/ML in 5G Radio Access Network
-	AI/ML for the 5G Physical Layer
-	AI/ML in 5G Services and Applications
-	AI/ML for 5G Network Management and Orchestration
-	Examples of AI/ML in 5G/B5G Use Cases Throughout the Tutorial


---

## Reading list


### 📝 Key Papers
- [Paper 1 Title](https://doi.org/xxx)
- [Paper 2 Title](https://doi.org/xxx)

### 💻 Code Repositories
- [GitHub Repo 1](https://github.com/yourname/repo1)
- [GitHub Repo 2](https://github.com/yourname/repo2)


