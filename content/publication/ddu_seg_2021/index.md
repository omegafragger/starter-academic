---
title: "Deep Deterministic Uncertainty for Semantic Segmentation"
authors:
- Jishnu Mukhoti
- Joost van Amersfoort
- Philip H.S. Torr
- Yarin Gal
date: "2021-10-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICML UDL Workshop, 2021*
publication_short: In *ICML UDL Workshop, 2021*

abstract: We extend Deep Deterministic Uncertainty (DDU), a method for uncertainty estimation using feature space densities, to semantic segmentation. DDU enables quantifying and disentangling epistemic and aleatoric uncertainty in a single forward pass through the model. We study the similarity of feature representations of pixels at different locations for the same class and conclude that it is feasible to apply DDU location independently, which leads to a significant reduction in memory consumption compared to pixel dependent DDU. Using the DeepLab-v3+ architecture on Pascal VOC 2012, we show that DDU improves upon MC Dropout and Deep Ensembles while being significantly faster to compute.

# Summary. An optional shortened abstract.
summary: Using DDU as a method for semantic segmentation provides epistemic and aleatoric uncertainty estimates from a single deterministic model, an improvement over previous methods like MC Dropout and Deep Ensembles.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://www.gatsby.ucl.ac.uk/~balaji/udl2021/accepted-papers/UDL2021-paper-089.pdf
# url_code: 'https://github.com/omegafragger/DDU'
# url_dataset: 'https://blackhc.github.io/ddu_dirty_mnist/'
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

