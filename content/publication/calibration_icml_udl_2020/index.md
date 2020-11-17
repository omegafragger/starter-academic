---
title: "On using Focal Loss for Neural Network Calibration"
authors:
- Jishnu Mukhoti, Viveka Kulharia, Amartya Sanyal, Stuart Golodetz, Philip H.S. Torr
- Puneet K. Dokania
date: "2020-12-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICML 2020, Workshop on Uncertainty and Robustness in Deep Learning*
publication_short: In *ICML UDL Workshop, 2020*

abstract: Miscalibration – a mismatch between a model’s confidence and its correctness – of Deep Neural Networks (DNNs) makes their predictions hard to rely on. Ideally, we want networks to be accurate and calibrated. In this work, we study focal loss as an alternative to the conventional cross-entropy loss and show that, focal loss allows us to learn models that are comparitively well calibrated while preserving accuracy. We provide a thorough analysis of the factors causing miscalibration, and use the insights we glean from this to justify the superior performance of focal loss. Finally, we perform extensive experiments on a variety of datasets, and with a wide variety of network architectures, and show that focal loss indeed achieves excellent calibration without compromising on accuracy in almost all cases.

# Summary. An optional shortened abstract.
summary: Propose focal loss as an alternative to cross-entropy loss for training well-calibrated, confident and accurate neural networks.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://www.gatsby.ucl.ac.uk/~balaji/udl2020/accepted-papers/UDL2020-paper-012.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: 'https://torrvision.github.io/focal_calibration'
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: ""
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

