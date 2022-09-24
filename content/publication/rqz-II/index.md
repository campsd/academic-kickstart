---
title: "A multishift, multipole rational QZ method with aggressive early deflation"
authors:
- Thijs Steel
- daan-camps
- karl-meerbergen
- raf-vandebril
date: "2021-05-27T00:00:00Z"
doi: "10.1137/19M1249631"

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

abstract: The rational QZ method generalizes the QZ method by implicitly supporting rational subspace iteration. In this paper we extend the rational QZ method by introducing shifts and poles of higher multiplicity in the Hessenberg pencil, which is a pencil consisting of two Hessenberg matrices. The result is a multishift, multipole iteration on block Hessenberg pencils which allows one to stick to real arithmetic for a real input pencil. In combination with optimally packed shifts and aggressive early deflation as an advanced deflation technique we obtain an efficient method for the dense generalized eigenvalue problem. In the numerical experiments we compare the results with state-of-the-art routines for the generalized eigenvalue problem and show that we are competitive in terms of speed and accuracy.


# Summary. An optional shortened abstract.
summary: An extension of the rational QZ method for the solution of the real generalized eigenvalue problems with aggressive early deflation.

tags:
- Pole swapping
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/1902.10954.pdf'
url_code: 'https://github.com/thijssteel/multishift-multipole-rqz'
url_dataset: ''
url_poster: ''
url_project: 'http://numa.cs.kuleuven.be/software/rqz/index.html'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Aggressive early deflation on block Hessenberg pencils'
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
