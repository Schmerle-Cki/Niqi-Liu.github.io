---
title: "Interpersonal Relationship Analysis with Dyadic EEG Signals via Learning Spatial-Temporal Patterns"
authors: "Wenqi Ji, Xinxin Du, Niqi Liu, Chao Zhou, Mingjin Yu, Guozhen Zhao, and Yong-Jin Liu"
date: "2024-01-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
 publication: "*arxiv preprint arXiv:2401.03250*"
publication_short: ""

abstract: "Interpersonal relationship quality is pivotal in social and occupational contexts. Existing analysis of interpersonal relationships mostly rely on subjective self-reports, whereas objective quantification remains challenging. In this paper, we propose a novel social relationship analysis framework using spatio-temporal patterns derived from dyadic EEG signals, which can be applied to quantitatively measure team cooperation in corporate team building, and evaluate interpersonal dynamics between therapists and patients in psychiatric therapy. First, we constructed a dyadic-EEG dataset from 72 pairs of participants with two relationships (stranger or friend) when watching emotional videos simultaneously. Then we proposed a deep neural network on dyadic-subject EEG signals, in which we combine the dynamic graph convolutional neural network for characterizing the interpersonal relationships among the EEG channels and 1-dimension convolution for extracting the information from the time sequence. To obtain the feature vectors from two EEG recordings that well represent the relationship of two subjects, we integrate deep canonical correlation analysis and triplet loss for training the network. Experimental results show that the social relationship type (stranger or friend) between two individuals can be effectively identified through their EEG data."

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Computational Social Science
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2401.03250
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

### Methodology: Dyadic EEG Dataset and Deep Neural Network

**Construction of Dyadic EEG Dataset:** We constructed a dyadic-EEG dataset from 72 pairs of participants with two types of relationships (stranger or friend) while they simultaneously watched emotional videos. This dataset serves as a foundation for analyzing the social relationships between individuals.

**Deep Neural Network for Dyadic EEG Signals:** A deep neural network was proposed to model the temporal and spatial information of EEG data. The network combines dynamic graph convolutional neural networks to characterize interpersonal relationships among EEG channels and 1-D convolution for extracting time sequence information. The framework integrates deep canonical correlation analysis and triplet loss for training the network, resulting in feature vectors that represent the relationship between two subjects.

### Key Findings: EEG Data and Social Relationship Identification

The experimental results demonstrate that the social relationship type (stranger or friend) between two individuals can be effectively identified through their EEG data. This finding has significant implications for understanding social dynamics and interpersonal connections in various social and occupational contexts.

### Conclusion: Advancing EEG-Based Research

The research shifts the focus from individual neural variations to interconnections in EEG patterns across individuals, providing a new perspective on EEG-based studies. The findings not only contribute to the understanding of interpersonal relationships but also offer a benchmark for future research in this novel area of study.
