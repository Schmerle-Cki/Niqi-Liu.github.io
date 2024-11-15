---
title: "A Multimodal Dataset for Mixed Emotion Recognition"
authors: "Pei Yang, Niqi Liu, Xinge Liu, Yezhi Shu, Wenqi Ji, Ziqi Ren, Jenny Sheng, Minjing Yu, Ran Yi, Dan Zhang, and Yong-Jin Liu"
author_notes:
- "Pei Yang, Niqi Liu, and Xinge Liu are with equal contribution"

date: "2024-08-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Scientific Data*, 11(1), 847"
publication_short: "SD"

abstract: Mixed emotions have attracted increasing interest recently, but existing datasets rarely focus on mixed emotion recognition from multimodal signals, hindering the affective computing of mixed emotions. On this basis, we present a multimodal dataset with four kinds of signals recorded while watching mixed and non-mixed emotion videos. To ensure effective emotion induction, we first implemented a rule-based video filtering step to select the videos that could elicit stronger positive, negative, and mixed emotions. Then, an experiment with 80 participants was conducted, in which the data of EEG, GSR, PPG, and frontal face videos were recorded while they watched the selected video clips. We also recorded the subjective emotional rating on PANAS, VAD, and amusement-disgust dimensions. In total, the dataset consists of multimodal signal data and self-assessment data from 73 participants. We also present technical validations for emotion induction and mixed emotion classification from physiological signals and face videos. The average accuracy of the 3-class classification (i.e., positive, negative, and mixed) can reach 80.96% when using SVM and features from all modalities, which indicates the possibility of identifying mixed emotional states.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Dataset
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.nature.com/articles/s41597-024-03676-4.pdf
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

### Constructing the Dataset: Emotion Induction and Data Collection

To ensure effective emotion induction, we employed a rule-based video filtering method to select videos capable of eliciting strong positive, negative, and mixed emotions. Data from 80 participants were collected, comprising multimodal signals and self-assessment data, providing a comprehensive view of emotional responses.

### Key Findings and Contributions

**Technical Validation and Emotion Classification:** Technical validations for emotion induction and classification used physiological signals and facial videos. Notably, the average accuracy of a 3-class classification (positive, negative, and mixed) reached 80.96% using SVM and features from all modalities, demonstrating the dataset's potential for identifying mixed emotional states.

### Implications and Future Research Directions

**Enabling Objective Assessment of Mixed Emotions:** This dataset addresses a significant gap in existing resources by focusing on mixed emotions, which are often overlooked in favor of discrete emotion classification. It provides a foundation for developing more nuanced emotion recognition systems and can inform future research in affective computing and emotional intelligence.