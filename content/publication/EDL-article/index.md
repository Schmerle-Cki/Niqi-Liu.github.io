---
title: "Emotion distribution learning based on peripheral physiological signals"
authors: "Yezhi Shu, Pei Yang, *Niqi Liu, Shu Zhang, Guozhen Zhao, and Yong-Jin Liu"
author_notes:
- "Yezhi Shu, Pei Yang, and Niqi Liu are with equal contribution"

date: "2022-03-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Affective Computing*, 14(3), 2470-2483"
publication_short: "TAFFC"
abstract: "Emotion analysis based on peripheral physiological signals has attracted increasing attention recently in affective computing. Previous works usually predict emotional states using a single emotion label for each discrete time. However, in real-world scenarios, it is not sufficient due to the fact that the real-world emotional state is usually a mixture of basic emotions. In this paper, we formulate the emotion analysis as an emotion distribution learning (EDL) problem and make two contributions. First, we establish a standardized dataset containing four negative emotions (anger, disgust, sadness, fear) and three positive emotions (tenderness, joy, amusement), which could be a useful benchmark for the EDL task. Second, we propose an emotion distribution prediction system that has the following distinct characteristics: (1) after processing raw peripheral physiological signals, we compute totally 89 representative features from four channels, i.e., GSR, SKT, ECG, and HR, (2) an adaptive feature selection strategy based on recursive feature elimination (RFE) is used to select the most significant features in our EDL task, and (3) we design a dedicated EDL model based on convolution neural networks that takes information from both the feature correlation and the time domain into consideration. Experiments were conducted to validate our proposed system, and the results indicated that (1) the proposed feature selection strategy effectively selects significant features and improves algorithmic performance, and (2) the proposed EDL model can obtain good results in terms of six evaluation measures and outperform existing methods."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- EDL
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9745388
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

**Key Contributions:**

1. **Dataset Creation:** We established a novel dataset that includes four negative emotions (anger, disgust, sadness, fear) and three positive emotions (tenderness, joy, amusement). This dataset, induced by movie clips and based on self-reports, serves as a benchmark for the EDL task.
2. **Emotion Distribution Prediction System:** The system processes raw peripheral physiological signals from four channels (GSR, SKT, ECG, HR) to compute 89 representative features. It employs an adaptive feature selection strategy using recursive feature elimination (RFE) and a convolutional neural network (CNN)-based EDL model that considers feature correlation and time domain information.

**Methodology:** The EDL model is designed to predict the intensity of basic emotions in a distribution, reflecting the mixed emotional states more accurately. The system includes data preprocessing to remove noise and drift, feature extraction from temporal and frequency domains, and a feature selection process to identify the most significant features for emotion distribution prediction.

**Results:** Experiments validate the proposed system, demonstrating that the feature selection strategy effectively enhances algorithmic performance. The EDL model outperforms existing methods across six evaluation measures, showing its efficacy in predicting emotion distributions based on peripheral physiological signals.
