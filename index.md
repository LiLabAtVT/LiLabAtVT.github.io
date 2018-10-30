---
layout: splash
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/header.jpeg
  cta_label: "Our GitHub Repository"
  cta_url: "https://github.com/LiLabAtVT"
excerpt: "We are driven by genomic data"
intro:
  - excerpt: 'Our research team focuses on developing computational tools for genome scale data analysis. The goal is to understand the connections between genotypes and phenotypes by developing computational algorithms that integrate large-scale data from genomics, transcriptomics, proteomics and metabolomics.'
feature_row:
  - image_path: /assets/images/regulatory_network.jpeg
    alt: "placeholder image 1"
    title: "Regulatory genomics"
    excerpt: "We are interested in developing computational tools to understand gene regulations in plant species."
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/field.jpg
    alt: "placeholder image 2"
    title: "Pathogen detection"
    excerpt: "We are interested in developing computaional tools to perform early detection of pathogen infection for plants."
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/soybean.jpg
    title: "Phenotype and GWAS study of soybean"
    excerpt: "We are interested in developing computational tools to associate the phenotype and genetic variation of soybean genome"
feature_row2:
  - image_path: /assets/images/regulatory_network.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/field.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/soybean.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
