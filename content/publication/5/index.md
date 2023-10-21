---
title: "Statistically unbiased prediction enables accurate denoising of voltage imaging data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Minho Eom
- Seungjae Han
- Pojeong Park
- Gyuri Kim
- Eun-Seo Cho
- Jueun Sim
- Kang-Han Lee
- Seonghoon Kim
- He Tian
- Urs L. Böhm
- Eric Lowet
- Hua-an Tseng
- Jieun Choi
- Stephani Edwina Lucia
- admin
- Márton Rózsa
- Sunghoe Chang
- Pilhan Kim
- Xue Han
- Kiryl D. Piatkevich
- Myunghwan Choi
- Cheol-Hee Kim
- Adam E. Cohen
- Jae-Byum Chang
- Young-Gyu Yoon 

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2023-09-18T00:00:00Z"
doi: "https://doi.org/10.1038/s41592-023-02005-8"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Nature Methods*
publication_short: In *Nat Methods*

abstract: Here we report SUPPORT (statistically unbiased prediction utilizing spatiotemporal information in imaging data), a self-supervised learning method for removing Poisson–Gaussian noise in voltage imaging data. SUPPORT is based on the insight that a pixel value in voltage imaging data is highly dependent on its spatiotemporal neighboring pixels, even when its temporally adjacent frames alone do not provide useful information for statistical prediction. Such dependency is captured and used by a convolutional neural network with a spatiotemporal blind spot to accurately denoise voltage imaging data in which the existence of the action potential in a time frame cannot be inferred by the information in other frames. Through simulations and experiments, we show that SUPPORT enables precise denoising of voltage imaging data and other types of microscopy image while preserving the underlying dynamics within the scene.



# Summary. An optional shortened abstract.
# summary: 


tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Nat Methods**](https://www.nature.com/articles/s41592-023-02005-8)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
