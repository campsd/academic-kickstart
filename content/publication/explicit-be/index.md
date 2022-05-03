---
title: "Explicit Quantum Circuits for Block Encodings of Certain Sparse Matrices"
authors:
- daan-camps
- Lin Lin
- roel-vanbeeumen
- Chao Yang
date: "2022-03-19T00:00:00Z"
doi: "10.48550/arXiv.2203.10236"

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

abstract: Many standard linear algebra problems can be solved on a quantum computer by using recently developed quantum linear algebra algorithms that make use of block encoding and quantum eigenvalue / singular value transformations. Block encoding embeds a properly scaled matrix of interest A in a larger unitary transformation U that can be decomposed into a product of simpler unitaries and implemented efficiently on a quantum computer. Although quantum algorithms can potentially achieve exponential speedup in solving linear algebra problems compared to the best classical algorithm, such gain in efficiency ultimately hinges on our ability to construct an efficient quantum circuit for the block encoding of A, which is difficult in general, and not trivial even for well structured sparse matrices. In this paper, we give a few examples on how efficient quantum circuits can be explicitly constructed for some well structured sparse matrices, and discuss a few strategies used in these constructions. We are particularly interested in sparse stochastic matrices that represent random walks on a graph, and show how the block encodings of such matrices yield efficient quantum walks.

# Summary. An optional shortened abstract.
summary: We provide explicit quantum circuits for the block encoding of certain sparse matrices.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://arxiv.org/pdf/2203.10236.pdf'
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
  caption: 'Detecting a marked vertex in a graph through a quantum walk'
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
