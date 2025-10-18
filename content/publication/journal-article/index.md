---
title: "Speech Emotion Recognition with Hybrid CNN- LSTM and Transformers Models: Evaluating the Hybrid Model Using Grad-CAM"
authors:
- admin
- Robert Ford
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Research in Computing, 4(II), 56–66*"
publication_short: ""

abstract: <p style="text-align: justify;">
    Emotional recognition and classification using artificial intelligence (AI) techniques play a crucial role in human-computer interaction (HCI). It enables the prediction of human emotions from audio signals with broad applications in psychology, medicine, education, entertainment, etc. This research focused on speech-emotion recognition (SER) by employing classification methods and transformer models using the Toronto Emotional Speech Set (TESS). Initially, acoustic features were extracted using different feature extraction techniques, including chroma, Mel-scaled spectrogram, contrast features, and Mel Frequency Cepstral Coefficients (MFCCs) from the audio dataset. Then, this study employed a Convolutional Neural Network (CNN), Long Short-Term Memory (LSTM), and a hybrid CNN-LSTM model to classify emotions. To compare the performance of these models, classical image transformer models such as ViT (Visual Image Transformer) and BEiT (Bidirectional Encoder Representation of Images) were employed on the Mel-spectograms derived from the same dataset. Evaluation metrics such as accuracy, precision, recall, and F1-score were calculated for each of these models to ensure a comprehensive performance comparison. According to the results, the hybrid model performed better than other models by achieving an accuracy of 99.01%, while the CNN, LSTM, ViT, and BEiT models demonstrated accuracies of 95.37%, 98.57%, 98%, and 98.3%, respectively. To interpret the output of this hybrid model and to provide visual explanations of its predictions, the Grad-CAM (Gradient-weighted Class Activation Mappings) was obtained. This technique reduced the black-box character of deep models, making them more reliable to use in clinical and other delicate contexts. In conclusion, the hybrid CNN-LSTM model showed strong performance in audio-based emotion classification. </p>

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
