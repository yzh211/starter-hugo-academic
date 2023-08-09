---
title: "An Assessment of Negative Samples and Model Structures in Landslide Susceptibility Characterization Based on Bayesian Network Models"
authors:
  - S Khabiri
  - MM Crawford
  - HJ Koch
  - WC Haneberg
  - Y Zhu
author_notes:
date: "2023-07-20"
doi: "https://doi.org/10.3390/rs15123200"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Remote Sensing*"
# publication_short: ""

abstract: Landslide susceptibility mapping (LSM) characterizes landslide potential, which is essential for assessing landslide risk and developing mitigation strategies. Despite the significant progress in LSM research over the past two decades, several long-standing issues, such as uncertainties related to training samples and model selection, remain inadequately addressed in the literature. In this study, we employed a physically based susceptibility model, PISA-m, to generate four different non-landslide data scenarios and combine them with mapped landslides from Magoffin County, Kentucky, for model training. We utilized two Bayesian network model structures, Naïve Bayes (NB) and Tree-Augmented Naïve Bayes (TAN), to produce LSMs based on regional geomorphic conditions. After internal validation, we evaluated the robustness and reliability of the models using an independent landslide inventory from Owsley County, Kentucky. The results revealed considerable differences between the most effective model in internal validation (AUC = 0.969), which used non-landslide samples extracted exclusively from low susceptibility areas predicted by PISA-m, and the models’ unsatisfactory performance in external validation, as manifested by the identification of only 79.1% of landslide initiation points as high susceptibility areas. The obtained results from both internal and external validation highlighted the potential overfitting problem, which has largely been overlooked by previous studies. Additionally, our findings also indicate that TAN models consistently outperformed NB models when training datasets were the same due to the ability to account for variables’ dependencies by the former.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Landslides
- Negative Samples
- Bayesian Network
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
  - risk

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
