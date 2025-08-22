---
title: "Effect of Missing Data Treatment on the Predictive Accuracy of C4.5 Classifier"
authors:
- admin
- Rehab Duwairi
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-03-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal on Communications Antenna and Propagation*"
publication_short: "IRECAP"

abstract: 'Missing data is a common problem confronted by researchers in machine learning applications. Missing values affect both the performance of analysis tools, as well as the quality of the drawn decisions. This research aims to analyze the impact of four missing data treatment methods on the predictive accuracy of the C4.5 decision tree algorithm. It also investigates the imputation accuracy of each imputation method using a single dataset with missing values presented in a single variable. The work was performed under three missing data assumptions, namely, Missing Completely At Random (MCAR), Missing At Random (MAR) and Missing Not At Random (MNAR) with three missingness’ rates: 5%, 10%, and 15%. The methods used to treat the missing data are: lite-wise deletion, mean/mode imputation, K-nearest neighbor imputation, and decision tree imputation. The results of the experiments showed that the C4.5 classifier achieved better performance under the MCAR assumption. While the mean/mode imputation has the highest C4.5 predictive accuracy under MAR and MNAR assumptions. The k-nearest neighbor method obtained the most accurate imputation result under the MCAR assumption, whereas mean/mode imputation was the most accurate method under the MAR assumption. On the other hand, the lowest imputation accuracy levels were achieved under the MNAR assumption attributed to the mean/mode imputation method'

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
    url: https://doi.org/10.15866/irecap.v11i3.19721
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: ""
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
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
