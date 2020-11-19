---
title: "On the Importance of Strong Baselines in Bayesian Deep Learning"
authors:
 - Jishnu Mukhoti
 - Pontus Stenetorp, Yarin Gal

date: "2018-12-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS, 2018 Workshop on Bayesian Deep Learning*
publication_short: In *NeurIPS 2018, BDL Workshop*

abstract: Like all sub-fields of machine learning Bayesian Deep Learning is driven by empirical validation of its theoretical proposals. Given the many aspects of an experiment it is always possible that minor or even major experimental flaws can slip by both authors and reviewers. One of the most popular experiments used to evaluate approximate inference techniques is the regression experiment on UCI datasets. However, in this experiment, models which have been trained to convergence have often been compared with baselines trained only for a fixed number of iterations. We find that a well-established baseline, Monte Carlo dropout, when evaluated under the same experimental settings shows significant improvements. In fact, the baseline outperforms or performs competitively with methods that claimed to be superior to the very same baseline method when they were introduced. Hence, by exposing this flaw in experimental procedure, we highlight the importance of using identical experimental setups to evaluate, compare, and benchmark methods in Bayesian Deep Learning.

# Summary. An optional shortened abstract.
summary: We re-evaluate MC Dropout by performing grid-search over dropout rates to generate significantly stronger baselines and compare MC Dropout with other state-of-the-art VI approaches.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://bayesiandeeplearning.org/2018/papers/42.pdf
url_code: 'https://github.com/yaringal/DropoutUncertaintyExps'
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

