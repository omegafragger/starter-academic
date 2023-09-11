---
title: "Fine-tuning can cripple your foundation model; preserving features may be the solution"
authors:
- Jishnu Mukhoti
- Yarin Gal
- Philip H.S. Torr
- Puneet K. Dokania
date: "2023-08-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In arxiv:2308.13320
publication_short: In arxiv:2308.13320

abstract: Pre-trained foundation models, owing primarily to their enormous capacity and exposure to vast amount of training data scraped from the internet, enjoy the advantage of storing knowledge about plenty of real-world concepts. Such models are typically fine-tuned on downstream datasets to produce remarkable state-of-the-art  performances. While various fine-tuning methods have been devised and are shown to be highly effective, we observe that a fine-tuned model's ability to recognize concepts on tasks *different* from the downstream one is reduced significantly compared to its pre-trained counterpart. This is clearly undesirable as a huge amount of time and money went into learning those very concepts in the first place. We call this undesirable phenomenon "concept forgetting" and via experiments show that most end-to-end fine-tuning approaches suffer heavily from this side effect. To this end, we also propose a rather simple fix to this problem by designing a method called LDIFS (short for l2 distance in feature space) that simply preserves the features of the original foundation model during fine-tuning. We show that LDIFS significantly reduces concept forgetting without having noticeable impact on the downstream task performance.

# Summary. An optional shortened abstract.
summary: We analyze and benchmark concept forgetting in foundation model fine-tuning and propose a simple fix to this phenomenon.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2308.13320.pdf
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
