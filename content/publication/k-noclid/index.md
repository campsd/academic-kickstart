---
title: "Non-Clifford diagonalization for measurement shot reduction in quantum expectation value estimation"
authors:
- nicolas-sawaya
- daan-camps
- norm-tubman
- Gramt M. Rotskoff
- Ryan LaRose
date: "2024-08-22T00:00:00Z"
doi: "10.48550/arXiv.2408.11898"


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

abstract: Estimating expectation values on near-term quantum computers often requires a prohibitively large number of measurements. One widely-used strategy to mitigate this problem has been to partition an operator's Pauli terms into sets of mutually commuting operators. Here, we introduce a method that relaxes this constraint of commutativity, instead allowing for entirely arbitrary terms to be grouped together, save a locality constraint. The key idea is that we decompose the operator into arbitrary tensor products with bounded tensor size, ignoring Pauli commuting relations. This method -- named k-NoCliD (k-local non-Clifford diagonalization) -- allows one to measure in far fewer bases in most cases, often (though not always) at the cost of increasing the circuit depth. We introduce several partitioning algorithms tailored to both fermionic and bosonic Hamiltonians. For electronic structure, vibrational structure, Fermi-Hubbard, and Bose-Hubbard Hamiltonians, we show that k-NoCliD reduces the number of circuit shots, often by a very large margin.

# Summary. An optional shortened abstract.
summary: In this paper, we introduce k-NoCliD, a method to reduce the number of measurements for estimating expectation values that relaxes the constraint of commutativity.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://arxiv.org/pdf/2408.11898'
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
  caption: 'Measurement variance for the spinless Fermi-Hubbard model with a variety of measurement strategies.'
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
