---
title: Home
---

# Biomedical Computing in the Department of Computer Science at UNC-Chapel Hill

We are collectively X labs in the [Department of Computer Science](https://cs.unc.edu) at UNC-Chapel Hill, working across diverse areas of biomedical computing, including, medical image analysis, computational immunology, computational genetics, and X. Marc, please scroll down where i have started to write about research areas. Maybe we should make a new page for the research areas in the header bar. 
  
{%
  include link.html
  type="github"
  icon=""
  text="Research Groups"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="Recent Publications"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner2.png" %}

{% include section.html %}

# Research Areas 

{% capture text %}
Advancements in high-throughput polychromatic flow cytometry technologies have enabled the ability to study the immune system at an unparalleled depth.  Understanding immunological adaptations to particular diseases and in aging and development offers unique opportunities to develop novel diagnostic tests or to propose specialized treatments or lifestyle interventions to optimize human health. Using single-cell flow and mass cytometry data collected across multiple individuals, our goal is to develop new computational techniques to identify and link heterogeneity in the cellular landscape to external variables of interest, such as, a clinical phenotype or diagnosis. To tackle these questions, we leverage advancements in machine learning, graph signal processing, and numerical linear algebra. Application areas of interest include pregnancy, neuroimmunology, and T-cell biology.

[See what we've published &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/immuno.png"
  link="research"
  headline="Computational Immunology"
  text=text
%}

{% capture text %}
Marc fill in

[See our resources &nbsp;→](resources)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  headline="Medical Image Analysis"
  text=text
%}

{% capture text %}
Leonard fill in

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  headline="Computational Genetics"
  text=text
%}
