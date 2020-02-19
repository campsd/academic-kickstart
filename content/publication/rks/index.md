---
title: "An implicit filter for rational Krylov using core transformations"
authors:
- admin
- Karl Meerbergen
- Raf Vandebril
date: "2019-01-15T00:00:00Z"
doi: "10.1016/j.laa.2018.09.021"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Linear Algebra and Applications*"
publication_short: ""

abstract: The rational Krylov method is a powerful tool for computing a selected subset of eigenvalues in large-scale eigenvalue problems. In this paper we study a method to implicitly apply a filter in a rational Krylov iteration by directly acting on a QR factorized representation of the Hessenberg pair from the rational Krylov method. This filter is used to restart the iteration, which is generally required to limit the orthogonalization and storage costs. The contribution in this paper is three- fold. We reformulate existing procedures in terms of operations on core transformations. This has the advantage of improved convergence monitoring. Secondly, we demonstrate that the extended QZ method is a special case of this more general method. Finally, numerical experiments show the validity and the increased accuracy of the new approach compared with existing methods.

# Summary. An optional shortened abstract.
summary: This article proposes numerical algorithms to filter and restart the rational Krylov sequence method.

tags:
- Pole swapping
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: files/reportRKS.pdf
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
  caption: 'Pole swapping via core transformations'
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
