---
title: Research
nav:
  order: 1
  tooltip: Research in the lab
---

# {% include icon.html icon="fa-solid fa-magnifying-glass" %}Research

Gene expression levels are precisely regulated during development, and even subtle perturbations to this process are a frequent cause of both rare and common human disease. Our overarching goal is to develop and apply tools to quantitatively perturb gene regulation to understand both its basic mechanisms and how this goes awry in disease. We combine chemical biology, functional genomics, stem cell modeling, and deep learning to address these questions across multiple biological scales. We primarily focus on transcription factors (TFs), key drivers of developmental regulatory programs that bind to noncoding regulatory DNA such as enhancers and promoters and modulate the production of RNA from target genes by recruiting cofactors.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Areas of focus

{% capture text %}

TFs are highly dosage-sensitive; quantitative changes of 50% or less in TF levels frequently cause rare disorders or common trait variation. However, we have lacked similarly quantitative tools to modulate TF function. Our work has been propelled by the advent of chemically induced proximity, where small molecules bring proteins of interest into physical proximity within the cell. We previously leveraged this approach to precisely reduce TF dosage in human pluripotent stem cell (hPSC)-derived cell types by recruiting E3 ligases to endogenous TFs. We are now expanding the system to stabilize TFs and increase their levels, and are also interested in increasing its throughput. Finally, we are using the power of chemically induced proximity to investigate aspects of TF function beyond dosage, such as TF-cofactor interactions.  


{% endcapture %}

{%
  include feature.html
  image="images/chemicalgenetics_tools.png"
  title="Tools to quantitatively manipulate TF function"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Neural crest cells are a powerful model for understanding cell fate control during development. This transient embryonic population gives rise to diverse cell types across the body, and its gene regulatory programs are reactivated in a range of cancers. TF haploinsufficiency is a major cause of neural crest-related developmental disorders. We are applying quantitative TF modulation in hPSC-derived neural crest models to mechanistically dissect how TF dosage controls cell fate decisions. We have used this approach to understand how TF dosage in cranial neural crest explains features of craniofacial disorders, and are now extending this platform to understand how vagal neural crest forms the nervous system of the gut and how disruptions lead to Hirschsprung disease. Ultimately, we aim to use these insights to the efficacy and functionality of cell therapies for regenerative medicine.


{% endcapture %}

{%
  include feature.html
  image="images/neuralcrest_dev.png"
  title="Transcriptional control of human neural crest development and disease"
  text=text
%}

{% capture text %}

Recent advances in machine learning and artificial intelligence have made substantial advances in learning the sequence features that predict cell type-specific chromatin and gene regulatory networks. However, most of these approaches rely on static, steady-state measurements. We recently developed a transfer learning with approach to predict how chromatin responds to TF dosage  perturbations, revealing hidden “layers” of the cis-regulatory code. Ultimately, we aim to accurately predict quantitative TF dosage effects in any cell type from sequence alone.

{% endcapture %}

{%
  include feature.html
  image="images/seqactivity_dl.png"
  title="Sequence-to-activity deep learning models to decode regulatory mechanisms"
  flip=true
  style="bare"
  text=text
%}

{% include section.html %}

