---
title: "Hyperparameter Transfer Learning with Adaptive Complexity"
authors:
- Samuel Horvath
- Aaron Klein
- Peter Richtarik
- Cedric Archambeau
date: "2021-01-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 24th International Conference on Artificial Intelligence and Statistics (AISTATS) 2021
publication_short: AISTATS 2021

abstract: Bayesian optimization (BO) is a sample efficient approach to automatically tune the hyperparameters of machine learning models. In practice, one frequently has to solve similar hyperparameter tuning problems sequentially. For example, one might have to tune a type of neural network learned across a series of different classification problems. Recent work on multi-task BO exploits knowledge gained from previous tuning tasks to speed up a new tuning task. However, previous approaches do not account for the fact that BO is a sequential decision making procedure. Hence, there is in general a mismatch between the number of evaluations collected in the current tuning task compared to the number of evaluations accumulated in all previously completed tasks. In this work, we enable multi-task BO to compensate for this mismatch, such that the transfer learning procedure is able to handle different data regimes in a principled way. We propose a new multi-task BO method that learns a set of ordered, nonlinear basis functions of increasing complexity via nested drop-out and automatic relevance hyperparameter tuning problems show that our method improves the sample efficiency of recently published multi-task BO methods.


links:
# - name: Custom Link
#   url: http://example.org
url_pdf: http://proceedings.mlr.press/v130/horvath21a/horvath21a.pdf
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
