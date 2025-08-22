---
title: "Retina Disorders Classification via OCT Scan: A Comparative Study between Self-Supervised Learning and Transfer Learning"
authors:
- admin
- Yazan Shannak
- Rehab Duwairi

author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2022-12-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*The International Arab Journal of Information Technology*"
publication_short: "IAJIT"

abstract: Retina disorders are among the common types of eye disease that occur due to several reasons such as aging, diabetes and premature born. Besides, Optical Coherence Tomography (OCT) is a medical imaging method that serves as a vehicle for capturing volumetric scans of the human eye retina for diagnoses purposes. This research compared two pretraining approaches including Self-Supervised Learning (SSL) and Transfer Learning (TL) to train ResNet34 neural architecture aiming at building computer aided diagnoses tool for retina disorders recognition. In addition, the research methodology employs convolutional auto-encoder model as a generative SSL pretraining method. The research efforts are implemented on a dataset that contains 109,309 retina OCT images with three medical conditions including Choroidal Neovascularization (CNV), Diabetic Macular Edema (DME), DRUSEN as well as NORMAL condition. The research outcomes showed better performance in terms of overall accuracy, sensitivity and specificity, namely, 95.2%, 95.2% and 98.4% respectively for SSL ResNet34 in comparison to scores of 90.7%, 90.7% and 96.9% respectively for TL ResNet34. In addition, SSL pretraining approach showed significant reduction in the number of epochs required for training in comparison to both TL pretraining as well as the previous research performed on the same dataset with comparable performance

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
  - type: doi
    url: https://doi.org/10.34028/iajit/20/3/8
  - type: code
    url: https://github.com/SaeedShurrab/OCT-Scans-Classification
  - type: dataset
    url: https://data.mendeley.com/datasets/rscbjbr9sj/3
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: ""
  # - type: video
  #   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
