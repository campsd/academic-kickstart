---
title: "A rational QZ method"
authors:
- daan-camps
- karl-meerbergen
- raf-vandebril
date: "2019-08-06T00:00:00Z"
doi: "10.1137/18M1170480"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*SIAM Journal on Matrix Analysis and Applications*"
publication_short: ""

abstract: We propose a rational QZ method for the solution of the dense, unsymmetric generalized eigenvalue problem. This generalization of the classical QZ method operates implicitly on a Hessenberg, Hessenberg pencil instead of on a Hessenberg, triangular pencil. Whereas the QZ method performs nested subspace iteration driven by a polynomial, the rational QZ method allows for nested subspace iteration driven by a rational function; this creates the additional freedom of selecting poles. In this article we study Hessenberg, Hessenberg pencils, link them to rational Krylov subspaces, propose a direct reduction method to such a pencil, and introduce the implicit rational QZ step. The link with rational Krylov subspaces allows us to prove essential uniqueness (implicit Q theorem) of the rational QZ iterates as well as convergence of the proposed method. In the proofs, we operate directly on the pencil instead of rephrasing it all in terms of a single matrix. Numerical experiments are included to illustrate competitiveness in terms of speed and accuracy with the classical approach. Two other types of experiments exemplify new possibilities. First we illustrate that good pole selection can be used to deflate the original problem during the reduction phase, and second we use the rational QZ method to implicitly filter a rational Krylov subspace in an iterative method.

# Summary. An optional shortened abstract.
summary: This article proposes a rational QZ method for the solution of the generalized eigenvalue problem.

tags:
- Pole swapping
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: files/M117048.pdf
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
  caption: 'Middle deflations in a rational QZ algorithm'
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
