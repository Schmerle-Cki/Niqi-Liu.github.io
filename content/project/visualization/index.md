---
title: Visualization of Public Opinions on ChatGPT
date: 2023-04-25
# external_link: https://github.com/Schmerle-Cki/LearningData/blob/master/DataVisualization/Technical%20Approach.pdf
tags:
  - Visualization
# {{< video src="">}}
# <video src="https://youtu.be/GSa7j948rW8" controls="controls" width="800" height="600"></video>
---
{{< video "https://youtu.be/GSa7j948rW8" >}}

Analyzed 55o,00o+ tweets, conducted sentiment analysis, and visualized emotional distribution.

#### Technical Approach

- **Tweet data download**
  Used 'python+selenium' framework, crawling:
  (1）<font color="blue">Tweets with the keyword '*ChatGPT*'</font>: 5.5 w+ (> 10 likes), including user name, posting time, number of reposts, comments and likes;
  (2） <font color="blue">The top 10,000+ OpenAI's followers' professional and geographical information</font>.
- **Tweet text processing**
  Used `python-nltk` package for word segmentation, `langdetect` package for language classification.
- **Tweet sentiment classification**
  Used <font color="blue">Twitter-Emotion-Recognition Emotion</font> six-category Model <font color="grey">(anger, disgust, fear, joy, sadness, surprise)</font> to identify the sentiment distribution of tweets.
- **Tweet sentiment distribution**
  Used the **PCA** dimensionality reduction visualization method, the 6-dimensional emotional vector is <font color="blue">reduced to a 2-dimensional plane coordinate vector</font>, and the radar chart displays the six-pole distribution of emotions. Mapping is
  established between <font color="blue">"tweet popularity ←→ bubble size"</font> and <font color="blue">"emotional vector ←→ bubble color"</font>.
- **Chart drawing**
  Mainly used **<font color="blue">d3.js</font>** and **<font color="blue">echarts</font>** to draw various charts, including the `d3.layout.cloud` library for word cloud diagrams and the `d3-geo-projection` library for maps.
- **Interaction Design**
  Mainly by hovering or clicking the mouse to get more information.

#### Architecture Description

- **<font color="blue">Front end</font>**: 	`d3.js` (90%), `echarts` (10%)
- **<font color="blue">Backend</font>**: 	  `VSCode Liver Server`  

<!--more-->
