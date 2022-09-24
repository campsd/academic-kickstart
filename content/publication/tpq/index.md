---
title: "Exploring Finite Temperature Properties of Materials with Quantum Computers"
authors:
- Connor Powers
- Lindsay Bassman Oftelie  
- daan-camps
- Wibe A. de Jong
date: "2022-08-25T00:00:00Z"
doi: "10.48550/arXiv.2109.01619"

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

abstract: Thermal properties of nanomaterials are crucial to not only improving our fundamental understanding of condensed matter systems, but also to developing novel materials for applications spanning research and industry. Since quantum effects arise at the nano-scale, these systems are difficult to simulate on classical computers. Quantum computers can efficiently simulate quantum many-body systems, yet current quantum algorithms for calculating thermal properties of these systems incur significant computational costs in that they either prepare the full thermal state on the quantum computer, or they must sample a number of pure states from a distribution that grows with system size. Canonical thermal pure quantum (TPQ) states provide a promising path to estimating thermal properties of quantum materials as they neither require preparation of the full thermal state nor require a growing number of samples with system size. Here, we present an algorithm for preparing canonical TPQ states on quantum computers. We compare three different circuit implementations for the algorithm and demonstrate their capabilities in estimating thermal properties of quantum materials. Due to its increasing accuracy with system size and flexibility in implementation, we anticipate that this method will enable finite temperature explorations of relevant quantum materials on near-term quantum computers.

# Summary. An optional shortened abstract.
summary: This paper introduces a two-step protocol to prepare thermal pure quantum states on a quantum computer.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: "arxiv.org/abs/2007.01417"
url_pdf: 'https://arxiv.org/pdf/2109.01619.pdf'
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
  caption: 'Thermal energy, as a function of inverse temperature for 1D Heisenberg models, calculated with TPQ states on a noiseless quantum simulator'
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
