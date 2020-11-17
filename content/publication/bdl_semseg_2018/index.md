---
title: "Evaluating Bayesian Deep Learning Methods for Semantic Segmentation"
authors:
- Jishnu Mukhoti
- Yarin Gal
date: "2019-03-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv:1811.12709*
publication_short: In *arXiv:1811.12709*

abstract: Deep learning has been revolutionary for computer vision and semantic segmentation in particular, with Bayesian Deep Learning (BDL) used to obtain uncertainty maps from deep models when predicting semantic classes. This information is critical when using semantic segmentation for autonomous driving for example. Standard semantic segmentation systems have well-established evaluation metrics. However, with BDL's rising popularity in computer vision we require new metrics to evaluate whether a BDL method produces better uncertainty estimates than another method. In this work we propose three such metrics to evaluate BDL models designed specifically for the task of semantic segmentation. We modify DeepLab-v3+, one of the state-of-the-art deep neural networks, and create its Bayesian counterpart using MC dropout and Concrete dropout as inference techniques. We then compare and test these two inference techniques on the well-known Cityscapes dataset using our suggested metrics. Our results provide new benchmarks for researchers to compare and evaluate their improved uncertainty quantification in pursuit of safer semantic segmentation.

# Summary. An optional shortened abstract.
summary: We propose new metrics to evaluate uncertainty estimates in semantic segmentation, evaluate Bayesian Deep Learning methods using these metrics and hence, create new benchmarks.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/1811.12709.pdf
# url_code: 'https://github.com/torrvision/focal_calibration'
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

