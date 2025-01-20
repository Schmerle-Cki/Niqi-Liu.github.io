---
title: "Temporal-Noise-Aware Neural Networks for Suicidal Ideation Prediction Using Physiological Data"
authors: "Niqi Liu, Fang Liu, Wenqi Ji, Xinxin Du, Xu Liu, Lan Wang, Guozhen Zhao, Wenting Mu, and Yong-Jin Liu"
date: "2025-01-09T00:00:00Z"
doi: "10.1109/TCSS.2024.3523928"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Computational Social Systems*"
publication_short: "TCSS"

abstract: The robust generalization of deep learning models in the presence of inherent noise remains a significant challenge, especially when labels are ambiguous due to their subjective nature and noise is indiscernible in natural settings. In this article, we address a specific and important scenario of monitoring suicidal ideation (SI), where time-series data, such as galvanic skin response (GSR) and photoplethysmography (PPG), are susceptible to such noise. Current methods predominantly focus on image and text data or address artificially introduced noise, neglecting the complexities of natural noise in time-series analysis. To tackle this, we introduce a novel neural network model tailored for analyzing noisy physiological time-series data, named DBN_ConvNet, which integrates advanced encoding techniques with confidence learning training to enhance prediction performance. Another main contribution of our work is the collection of a specialized dataset of GSR and PPG signals derived from real-world environments for SI prediction. By employing this dataset, our DBN_ConvNet achieves a prediction accuracy of 76.67% and an F1 score of 0.74 in a binary classification task, outperforming state-of-the-art methods. Furthermore, comprehensive evaluations have been conducted on three other well-known public datasets with artificially introduced noise to test the DBN_ConvNet’s capabilities rigorously. These tests consistently demonstrated DBN_ConvNet’s superior performance by achieving an improvement of more than 10% in both accuracy and F1 score compared to the baseline methods.

# Summary. An optional shortened abstract.
summary: In this paper, we introduce DBN_ConvNet, a neural network model designed to analyze noisy physiological time-series data, specifically for monitoring suicidal ideation. DBN_ConvNet combines advanced encoding with confidence learning to improve prediction accuracy, addressing the challenge of natural noise in GSR and PPG data. Our model outperforms existing methods, achieving 76.67% accuracy on a binary classification task using a real-world peripheral physiological dataset. Additionally, DBN_ConvNet demonstrated over 10% accuracy improvement on three public datasets with artificially introduced noise.

tags:
- Computational Neuroscience
- Mental Health

featured: true

# links:
# - name: TNANet
#   url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/10836135
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: https://github.com/Schmerle-Cki/Biometric-Suicidal-Ideation-Database
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false
video:
    caption: 'Video Sourcs: [**Unsplahs**](https://youtu.be/GSa7j948rW8)'
    focal_point: ""
    preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

It focuses on rapid screening within high–risk populations, driven by the urgent need for early detection of suicidal ideation in individuals skilled at masking their emotions. Timely intervention in these cases can be life–saving. Collaborating with a healthcare institution for data collection, I tackled a binary classification task complicated by two main challenges: scarce–category issues and label uncertainty. Suicidal ideation cases are rare, and false negatives often arise due to subjective judgments by non–expert annotators. To overcome these obstacles, I stratified the data based on label certainty and developed a semi–supervised learning pipeline that integrated nonparametric noise filtering techniques, primarily confidence learning, into deep neural networks. This approach significantly outperformed state–of–the–art models, improving classification metrics by 14.17 percent on our custom dataset and showing superior performance on public time–series datasets. Moreover, it effectively identified mislabeled cases, improving overall model reliability. The methodologies I developed are now being applied to assess suicidal ideation in the ABCD® study and to evaluate personality traits in another dataset, demonstrating versatility and potential for broader applications, such as health monitoring in high–stress professions like aviation.
