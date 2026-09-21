---
layout: about
title: About
permalink: /
subtitle: Postdoctoral Researcher, AIRLab - Politecnico di Milano

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page (moved next to the bio instead)

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="bio-block" markdown="1">
I am a postdoctoral researcher at the [Artificial Intelligence and Robotics Laboratory (AIRLab)](https://airlab.deib.polimi.it/) of Politecnico di Milano, where my research focuses on <span style="color: var(--global-theme-color);">trustworthy scientific machine learning</span>: I build <span style="color: var(--global-theme-color);">geometry- and physics-aware architectures</span> that exploit the natural structure of real-world systems and signals, tackling <span style="color: var(--global-theme-color);">generative modeling</span> and <span style="color: var(--global-theme-color);">uncertainty quantification</span> in applied physical settings.

If you are interested in my work or think there might be room for collaboration, don't hesitate to reach out.

<div class="social">
  {% assign email_parts = site.data.socials.email | split: "@" %}
  <div class="contact-lines">
    <a href="#" class="al-email-protect" data-eu="{{ email_parts[0] }}" data-ed="{{ email_parts[1] }}">[<i class="fa-solid fa-envelope"></i> <span class="label">E-mail</span>]</a>
    <a href="https://scholar.google.com/citations?user={{ site.data.socials.scholar_userid }}" title="Google Scholar">[<i class="fa-solid fa-graduation-cap"></i> <span class="label">Google Scholar</span>]</a>
  </div>
</div>
</div>

## Research

<div class="publications research-list">
<ol class="bibliography">

<li>
<div class="row">
  <div class="col-sm-2 abbr">
    {% include figure.liquid path="/assets/img/research/trustworthy-ml.jpg" class="preview img-fluid z-depth-1 rounded" alt="Trustworthy and robust scientific machine learning" %}
  </div>
  <div class="col-sm-8">
    <div class="title">Trustworthy and robust scientific machine learning</div>
    <div class="periodical">Developing machine learning models for scientific and engineering applications that stay reliable and well-calibrated when deployed in complex, real-world conditions.</div>
  </div>
</div>
</li>

<li>
<div class="row">
  <div class="col-sm-2 abbr">
    {% include figure.liquid path="/assets/img/research/geometry-physics.jpg" class="preview img-fluid z-depth-1 rounded" alt="Geometry- and physics-aware architectures" %}
  </div>
  <div class="col-sm-8">
    <div class="title">Geometry- and physics-aware architectures</div>
    <div class="periodical">Designing neural architectures that encode the geometric and physical structure of the systems they model, improving sample efficiency and generalization.</div>
  </div>
</div>
</li>

<li>
<div class="row">
  <div class="col-sm-2 abbr">
    {% include figure.liquid path="/assets/img/research/generative-uq.jpg" class="preview img-fluid z-depth-1 rounded" alt="Generative modeling and uncertainty quantification" %}
  </div>
  <div class="col-sm-8">
    <div class="title">Generative modeling and uncertainty quantification</div>
    <div class="periodical">Building generative models that produce realistic outputs while quantifying their own uncertainty in applied physical settings.</div>
  </div>
</div>
</li>

<li>
<div class="row">
  <div class="col-sm-2 abbr">
    {% include figure.liquid path="/assets/img/research/differential-geometry.jpg" class="preview img-fluid z-depth-1 rounded" alt="Latent representation geometries" %}
  </div>
  <div class="col-sm-8">
    <div class="title">Latent representation geometries</div>
    <div class="periodical">Using tools from differential geometry to shape and analyze the latent spaces learned by generative and representation-learning models.</div>
  </div>
</div>
</li>

<li>
<div class="row">
  <div class="col-sm-2 abbr">
    {% include figure.liquid path="/assets/img/research/digital-twins-em.jpg" class="preview img-fluid z-depth-1 rounded" alt="Digital twins of the electromagnetic environment" %}
  </div>
  <div class="col-sm-8">
    <div class="title">Digital twins of the electromagnetic environment</div>
    <div class="periodical">Developing efficient, reliable, and physically grounded models for electromagnetic wave propagation to support next-generation wireless communication in complex urban settings.</div>
  </div>
</div>
</li>

</ol>
</div>
