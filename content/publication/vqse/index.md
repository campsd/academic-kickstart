---
title: "Chemistry on quantum computers with virtual quantum subspace expansion"
authors:
- Miroslav Urbanek
- daan-camps
- roel-vanbeeumen
- Wibe A. de Jong
date: "2020-02-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Several novel methods for performing calculations relevant to quantum chemistry on quantum computers have been proposed but not yet explored experimentally. Virtual quantum subspace expansion [T. Takeshita et al., Phys. Rev. X 10, 011004 (2020)] is one such algorithm developed for modeling complex molecules using their full orbital space and without the need for additional quantum resources. We implement this method on the IBM Q platform and calculate the potential energy curves of the hydrogen and lithium dimers using only two qubits and simple classical post-processing. A comparable level of accuracy would require twenty qubits with previous approaches. We also develop an approach to minimize the impact of experimental noise on the stability of a generalized eigenvalue problem that is a crucial component of the algorithm. Our results demonstrate that virtual quantum subspace expansion works well in practice.

# Summary. An optional shortened abstract.
summary: This article experimentally verifies the virtual quantum subspace expansion by computing energy curves of hydrogen and lithium.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: "arxiv.org/abs/2002.12902"
url_pdf: 'https://arxiv.org/pdf/2002.12902.pdf'
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
  caption: 'H2 energy levels'
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
