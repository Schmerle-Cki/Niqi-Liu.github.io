---
title: 'Emotion Recognition from Few-Channel EEG Signals by Integrating Deep Feature Aggregation and Transfer Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: "Fang Liu, Pei Yang, Yezhi Shu, *Niqi Liu, Jenny Sheng, Junwen Luo, Xiaoan Wang, and Yong-Jin Liu"

date: '2023-11-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Affective Computing*, 15(3), 1315-1330"
publication_short: "TAFFC"

abstract: Electroencephalogram (EEG) signals have been widely studied in human emotion recognition. The majority of existing EEG emotion recognition algorithms utilize dozens or hundreds of electrodes covering the whole scalp region (denoted as full-channel EEG devices in this paper). Nowadays, more and more portable and miniature EEG devices with only a few electrodes (denoted as few-channel EEG devices in this paper) are emerging. However, emotion recognition from few-channel EEG data is challenging because the device can only capture EEG signals from a portion of the brain area. Moreover, existing full-channel algorithms cannot be directly adapted to few-channel EEG signals due to the significant inter-variation between full-channel and few-channel EEG devices. To address these challenges, we propose a novel few-channel EEG emotion recognition framework from the perspective of knowledge transfer. We leverage full-channel EEG signals to provide supplementary information, available online, for few-channel signals via a transfer learning-based model CD-EmotionNet , which consists of a base emotion model for efficient emotional feature extraction and a cross-device transfer learning strategy. This strategy helps to enhance emotion recognition performance on few-channel EEG data by utilizing knowledge learned from full-channel EEG data. To evaluate our cross-device EEG emotion transfer learning framework, we construct an emotion dataset containing paired 18-channel and 5-channel EEG signals from 25 subjects, as well as 5-channel EEG signals from 13 other subjects. Extensive experiments show that our framework outperforms state-of-the-art EEG emotion recognition methods by a large margin.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Transfer Learning
  - Affective Computing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10328701'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

**Key Contributions:**

1. The development of a base emotion model that employs graph convolutional networks (GCNs) and a feature aggregation mechanism to extract robust emotional features from EEG data.
2. The creation of the CDEED dataset, comprising paired 18-channel and 5-channel EEG signals from 25 subjects, providing a benchmark for cross-device EEG emotion recognition.
3. Extensive experiments demonstrating the superiority of the proposed framework over state-of-the-art methods, showcasing significant improvements in emotion recognition accuracy using few-channel EEG signals.

**Methodology:** Our approach integrates a base emotion model inspired by the Vector of Locally Aggregated Descriptors (VLAD) for compact global representation and a cross-device transfer learning strategy based on Model-Agnostic Meta-Learning (MAML). This strategy facilitates the enhancement of emotion recognition on few-channel EEG data by utilizing knowledge learned from full-channel EEG data, leading to improved performance in real-world applications.

**Conclusion:** The proposed CD-EmotionNet framework achieves state-of-the-art performance in few-channel EEG emotion recognition tasks, highlighting its potential for everyday applications of EEG signals in human-computer interaction and mental health monitoring.
