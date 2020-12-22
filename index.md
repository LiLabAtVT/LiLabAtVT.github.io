---
layout: splash
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/header.jpeg
  cta_label: "Our GitHub Repository"
  cta_url: "https://github.com/LiLabAtVT"
excerpt: "We are driven by the revolution of big data and AI in plant biology and agriculture."
intro:
  - excerpt: 'Our research focuses on developing computational tools for genomic and phenomic data analysis. 
              We are interested in understanding the connections between genotypes and phenotypes. 
              Our approach is to use interpretable machine learning methods to extract meaningful information from big data and to make actionable predictions.'

feature_row:
  - image_path: /assets/images/myb_network.png
    alt: "placeholder image 1"
    title: "Regulatory genomics"
    excerpt: "Understand gene regulation using networks."
    url: /research/CoReg/
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/field.jpeg
    alt: "placeholder image 2"
    title: "Pathogen detection"
    excerpt: "Early detection of plant diseases."
    url: "https://github.com/LiLabAtVT"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/soybean.jpeg
    title: "Phenomics and GWAS"
    excerpt: "Associate phenotypes with genetic variations"
    url: "https://github.com/LiLabAtVT"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/machine_learning.jpg
    alt: "placeholder image 2"
    title: "Machine learning"
    excerpt: 'We utilize advanced statistical and machine learning methods in genomics and phenomics research'
    url: "https://github.com/LiLabAtVT"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/plants.jpeg
    alt: "placeholder image 2"
    title: "Plant and microbial genomes"
    excerpt: 'We apply computational tools to study genomes of plant and microbial species'
    url: "https://github.com/LiLabAtVT"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="center" %}

{% include feature_row id="feature_row3" type="center" %}
