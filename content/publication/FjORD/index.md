---
title: "FjORD: Fair and Accurate Federated Learning under heterogeneous targets with Ordered Dropout"
authors:
- Samuel Horvath
- Stefanos Laskaridis
- Mario Almeida
- Ilias Leontiadis
- Stylianos Venieris
- Nicholas Lane
date: "2021-02-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Arxiv
publication_short: Arxiv

abstract: Federated Learning (FL) has been gaining significant traction across different ML tasks, ranging from vision to keyboard predictions. In large scale deployments, client heterogeneity is a fact, and constitutes a primary problem for fairness, significant efforts have been made into tackling statistical data heterogeneity, the diversity in the clients, termed as system heterogeneity, has remained largely unexplored. Current solutions either disregard a large portion of available devices or set a uniform limit on the model’s capacity, restricted by the least capable participants. In this work, we introduce Ordered Dropout, a mechanism that achieves an ordered, nested representation of knowledge in Neural Networks and enables the extraction of lower footprint submodels without the need of retraining. We further show that for linear maps our Ordered Dropout is equivalent to SVD. We employ this technique, along with a self-distillation methodology, in the realm of FL in a framework called FjORD. FjORD alleviates the problem of client system heterogeneity by tailoring the model width to the client’s capabilities. Extensive evaluation on both CNNs and RNNs across diverse modalities shows that FjORD consistently leads to significant performance gains over state-of-the-art baselines, while maintaining its nested structure.


links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2102.13451.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: http://2018.ds3-datascience-polytechnique.fr/wp-content/uploads/2018/06/DS3-342.pdf
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
