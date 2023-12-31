---
title: Research
nav:
  order: 1
  tooltip: Research in the lab
---

# {% include icon.html icon="fa-solid fa-magnifying-glass" %}Research

Gene expression levels are precisely regulated during development; quantitative perturbations to this process are a frequent cause of both rare and common human disease. However, most experimental tools that have been applied to study gene function are binary in nature. Therefore, our overarching goal is to develop and apply tools to quantitatively perturb gene regulation to understand both basic mechanisms of gene regulation and how this goes awry in disease.

Much of the lab's work centers on transcription factors (TFs), proteins that bind to noncoding regulatory DNA such as enhancers and promoters and modulate the production of RNA from target genes. TFs are highly dosage-sensitive - quantitative changes of 50% or less in TF levels frequently cause rare disorders or common trait variation.   

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Areas of focus

{% capture text %}

In addition to being dosage-sensitive, TFs are pleiotropic - one TF can have important roles in multiple cell types. Despite these broad roles, TF dosage sensitivity typically impacts one or a few cell types. To understand what drives this specificity, we study the human neural crest, a transient, embryonic cell population that gives rise to a fascinating array of cell types and tissues. Understanding why specific neural crest lineages are sensitive to dosage of broadly important TFs will yield new insights into developmental disorders that affect organ systems as diverse as the face, as in craniofacial malformations, and the gut, such as the loss of the enteric nervous system in Hirschsprung's disease.   


{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="Cell type specificity of TF dosage sensitivity"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Recent advances in machine learning and artifical intelligence have made substantial advances in learning the sequence features that predict cell type-specific chromatin and gene regulatory networks. However, the vast majority of these approaches rely on static, steady-state measurements. We are combining deep learning approaches with quantitative perturbations and functional genomic data to reveal hidden layers of the cis-regulatory code. Ultimately, we aim to accurately predict quantitative TF dosage effects in any cell type, from sequence alone.


{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="Machine learning to decode gene regulatory mechanisms"
  text=text
%}

{% capture text %}

We and others have developed and applied degron-based approaches that can precisely manipulate protein levels, but with low throughput. CRISPR-based methods for titrating gene expression are higher throughput, but with lower precision. We aim to develop both arrayed and pooled assays for precise manipulation of protein levels for dozens to hundreds of genes in a single experiment. Such methods could be used to quantitatively assay essentially every expressed TF in a given cell type, allowing us to query why some TFs are more dosage-sensitive than others.

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="Expanding the scope and scale of quantitative perturbations"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

While TFs are defined by their molecular function as regulators of gene expression, their dosage changes ultimately cause disease by resulting in specific changes to cellular behavior and/or tissue morphology and growth. We are combining stem cell-derived organoid models of human development with live-cell imaging to understand how quantitative changes in TF dosage percolate through different levels of scale. We hope that this integrated platform will reveal novel therapeutic approaches to prevent or reverse dosage-sensitive developmental disorders.      

{% endcapture %}

{%
  include feature.html
  image="images/sphere_confocal.jpg"
  title="From TF dosage to cellular and morphological outcomes"
  text=text
%}

{% include section.html %}

