---
title: "Stochastic Distributed Learning with Gradient Quantization and Variance Reduction"
authors:
- Samuel Horvath
- Dmitry Kovalev
- Konstantin Mishchenko
- Sebastian Stich
- Peter Richtarik
date: "2019-04-01T00:00:00Z"
doi: ""
# Schedule page publish date (NOT publication's date).
publishDate: "2019-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Arxiv
publication_short: Arxiv

abstract:  We consider distributed optimization where the objective function is spread among different devices, each sending incremental model updates to a central server. To alleviate the communication bottleneck, recent work proposed various schemes to compress (e.g. quantize or sparsify) the gradients, thereby introducing additional variance hat might slow down convergence. For strongly convex functions distributed among n machines,  we give a scheme that converges linearly to a neighborhood of the optimal solution. For objective functions with a finite-sum structure, each worker having less than m components, we present novel variance reduced schemes that converge linearly to arbitrary accuracy. These are the first methods that achieve linear convergence for arbitrary quantized updates. We also give analysis for the weakly convex and non-convex cases and we verify in experiments that our novel variance reduced schemes are more efficient than the baselines.




links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/1904.05115.pdf
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
