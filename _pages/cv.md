---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Biological Sciences, University of Cambridge, 2025
* MSc in Genome Science and Technology, University of British Columbia, 2019
* BSc (Honours) in Genome Biology and Evolutionary Biology, University of Toronto, 2015

Work experience
======

* 2026: Bioinformatician, Sanger Institute
  * Developed workflows for the integration and analysis of subcellular spatial transcriptomics data
  * Assisted with collaborator analyses, focusing on multimodal data integration and analysis of spatial tran-
scriptomics data

* 2021–2025: Postgraduate researcher, Sanger Institute
  * Led data analysis for the GBMspace project using the latest computational methods for integrative analysis of single nucleus multiome sequencing, spatial transcriptomics, and spatial genomics data (see Publica- tions)
  * Assisted with experimental design, including LCM sampling strategies for spatial genomics data generation
  * Assisted with data quality control during data generation phase of GBMspace
  * Assisted collaborators with subsequent analyses and in a consultatory context for biological interpretation
of data

* 2020-2021: Bioinformatician at Canexia Health
  * Helped develop a plasma-based oncogenomic panel targeting low-VAF mutations from cfDNA
  * Assisted with longitudinal cancer studies
  * Optimized FFPE-based cancer screen
  
* 2016-2019: Graduate Researcher (Adams Lab)
  * Generated lab pipelines forthe analysis of duplicate gene expression
  * Developed a pipeline forthe detection and quantitative comparison of
alternative splicing events
  * Supervised an undergraduate research project with the goal of familiarizing the
student with HPC best practices using Compute Canada resources
  * Performed the role of lab server administrator
  * Completed two projects pertaining to evolutionary plant transcriptomics (see
below for more detail)
  
Skills
======

* Programming
  * Python, R, Bash, NextFlow
  
* Omics expertise
  * Spatial transcriptomics (Visium, Xenium), conventional transcriptomics (single cell RNA-seq, bulk RNA-seq), genomics (single cell DNA-seq, bulk WGS), ATAC (multiome-derived single cell ATAC-seq)
  
* Common analysis pipelines
  * Atlas-level single cell data integration (e.g. scvi-tools), cell type deconvolution of spatial transcriptomics data, atlas-level label transfer or ”surgery” pipelines, RNA velocity inference, WGS variant detection, cell-cell communication inference.

* Machine learning
  * PyTorch-based probabilistic models (e.g. scvi-tools), scikit-learn models (e.g. for classification, clustering, dimensionality reduction, matrix decomposition (NMF), parameter optimisation).
  
* Technical
  * HPC best practices, Pipeline development, Git and GitHub, Microsoft Azure, AWS, Server administration
  
* Molecular Biology
  * Sequencing library preparation, RNA/DNA extractions, RT-PCR, basic protein identification (e.g.GC-MS)

Publications
======

  {% assign publications = site.publications | sort: "date" | reverse %}
  <ul>{% for post in publications %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>
  
Talks
======

  {% assign talks = site.talks | sort: "date" | reverse %}
  <ul>{% for post in talks %}
      {% include archive-single-talk-cv.html %}
    {% endfor %}</ul>
  
Teaching
======

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
