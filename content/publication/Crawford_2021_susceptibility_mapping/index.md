---
title: "Using landslide-inventory mapping for a combined bagged-trees and logistic-regression approach to determining landslide susceptibility in eastern Kentucky, USA"
authors:
  - MM Crawford
  - JM Dortch
  - HJ Koch
  - AA Killen
  - J Zhu
  - Y Zhu
  - LS Bryson
  - WC Haneberg
author_notes:
date: "2021-11-04"
doi: "https://doi.org/10.1144/qjegh2020-177"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Quarterly Journal of Engineering Geology and Hydrogeology*"
# publication_short: ""

abstract: High-resolution LiDAR-derived datasets from a 1.5 m digital elevation model and a detailed landslide inventory (n ≥ 1000) for Magoffin County, Kentucky, USA were used to develop a combined machine-learning and statistical approach to improve geomorphic-based landslide-susceptibility mapping. An initial dataset of 36 variables was compiled to investigate the connection between slope morphology and landslide occurrence. Bagged trees, a machine-learning random-forest classifier, was used to evaluate the geomorphic variables, and 12 were identified as important standard deviation of plan curvature, standard deviation of elevation, sum of plan curvature, minimum slope, mean plan curvature, range of elevation, sum of roughness, mean curvature, sum of curvature, mean roughness, minimum curvature and standard deviation of curvature. These variables were further evaluated using logistic regression to determine the probability of landslide occurrence and then used to create a landslide-susceptibility map. The performance of the logistic-regression model was evaluated by the receiver operating characteristic curve, area under the curve, which was 0.83. Standard deviations from the probability mean were used to set landslide-susceptibility classifications low (0–0.10), low–moderate (0.11–0.27), moderate (0.28–0.44), moderate–high (0.45–0.61) and high (0.62–1.0). Logistic-regression results were validated by using a separate landslide inventory for the neighbouring Prestonsburg 7.5-minute quadrangle, and running the same regression function. Results indicate that 74.9% of the landslide deposits were identified as having moderate, moderate–high or high landslide susceptibility. Combining inventory mapping with statistical modelling identified important geomorphic variables and produced a useful approach to landslide-susceptibility mapping.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Landslide
- Susceptibility Mapping
- Machine Learning

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
