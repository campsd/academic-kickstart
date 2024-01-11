---
title: "Quantum Fourier Transform Revisited"
authors:
- daan-camps
- roel-vanbeeumen
- chao-yang
date: "2020-09-15T00:00:00Z"
doi: "10.1002/nla.2331"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Numerical Linear Algebra with Applications"
publication_short: "Numer Linear Algebra Appl."

abstract: The fast Fourier transform (FFT) is one of the most successful numerical algorithms of the 20th century and has found numerous applications in many branches of computational science and engineering. The FFT algorithm can be derived from a particular matrix decomposition of the discrete Fourier transform (DFT) matrix. In this paper, we show that the quantum Fourier transform (QFT) can be derived by further decomposing the diagonal factors of the FFT matrix decomposition into products of matrices with Kronecker product structure. We analyze the implication of this Kronecker product structure on the discrete Fourier transform of rank-1 tensors on a classical computer. We also explain why such a structure can take advantage of an important quantum computer feature that enables the QFT algorithm to attain an exponential speedup on a quantum computer over the FFT algorithm on a classical computer. Further, the connection between the matrix decomposition of the DFT matrix and a quantum circuit is made. We also discuss a natural extension of a radix-2 QFT decomposition to a radix-d QFT decomposition. No prior knowledge of quantum computing is required to understand what is presented in this paper. Yet, we believe this paper may help readers to gain some rudimentary understanding of the nature of quantum computing from a matrix computation point of view.

# Summary. An optional shortened abstract.
summary: An introduction to the quantum Fourier transform from a matrix analysis perspective that provides an alternative derivation of the algorithm.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://arxiv.org/pdf/2003.03011.pdf'
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
  caption: 'Quantum circuit'
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
