---
title: "Deep Deterministic Uncertainty: A New Simple Baseline"
authors:
- Jishnu Mukhoti
- Andreas Kirsch
- Joost van Amersfoort
- Philip H.S. Torr
- Yarin Gal
date: "2023-03-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In IEEE/CVF Computer Vision and Pattern Recognition Conference, 2023 (Highlight)
publication_short: In CVPR 2023 (Highlight)

abstract: Reliable uncertainty from deterministic single-forward pass models is sought after because conventional methods of uncertainty quantification are computationally expensive. We take two complex single-forward-pass uncertainty approaches, DUQ and SNGP, and examine whether they mainly rely on a well-regularized feature space. Crucially, without using their more complex methods for estimating uncertainty, a single softmax neural net with such a feature-space, achieved via residual connections and spectral normalization, *outperforms* DUQ and SNGP's epistemic uncertainty predictions using simple Gaussian Discriminant Analysis *post-training* as a separate feature-space density estimator -- without fine-tuning on OoD data, feature ensembling, or input pre-procressing. This conceptually simple *Deep Deterministic Uncertainty (DDU)* baseline can also be used to disentangle aleatoric and epistemic uncertainty and performs as well as Deep Ensembles, the state-of-the art for uncertainty prediction, on several OoD benchmarks (CIFAR-10/100 vs SVHN/Tiny-ImageNet, ImageNet vs ImageNet-O) as well as in active learning settings across different model architectures, yet is *computationally cheaper*.

# Summary. An optional shortened abstract.
summary: A deterministic deep neural network with sensitivity and smoothness (bi-Lipschitz) constraints on its feature space can be used to quantify epistemic uncertainty from an estimate of density in feature space and aleatoric uncertainty from the entropy of its softmax distribution.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2102.11582.pdf
url_code: 'https://github.com/omegafragger/DDU'
url_dataset: 'https://blackhc.github.io/ddu_dirty_mnist/'
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

