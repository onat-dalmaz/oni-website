---
title: 'A Specificity-Preserving Generative Model for Federated MRI Translation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Usama Mirza
- Gökberk Elmas
- Muzaffer Özbey
- Salman UH Dar
- Tolga Cukur

# Author notes (optional)

date: '2022-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *MICCAI Workshop on “Distributed, Collaborative and Federated Learning” (MICCAI-DeCaF)*
publication_short: In *MICCAI-DeCaF*

abstract: MRI translation models learn a mapping from an acquired source contrast to an unavailable target contrast. Collaboration between institutes is essential to train translation models that can generalize across diverse datasets. That said, aggregating all imaging data and training a centralized model poses privacy problems. Recently, federated learning (FL) has emerged as a collaboration framework that enables decentralized training to avoid sharing of imaging data. However, FL-trained translation models can deteriorate by the inherent heterogeneity in the distribution of MRI data. To improve reliability against domain shifts, here we introduce a novel specificity-preserving FL method for MRI contrast translation. The proposed approach is based on an adversarial model that adaptively normalizes the feature maps across the generator based on site-specific latent variables. Comprehensive FL experiments were conducted on multi-site datasets to show the effectiveness of the proposed approach against prior federated methods in MRI contrast translation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: IEEE Xplore
#   url: https://ieeexplore.ieee.org/document/9643358

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
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
