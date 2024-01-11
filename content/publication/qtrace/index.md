---
title: "Efficient Quantum Trace Estimation with Reconfigurable Real-Time Circuits"
authors:
- yizhi-shen
- katie-klymko
- Eran Rabani
- daan-camps
- roel-vanbeeumen
- Michael Lindsey
date: "2024-01-08T00:00:00Z"
doi: "10.48550/arXiv.2401.04176"

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

abstract: Recently, quantum algorithms that leverage real-time evolution under a many-body Hamiltonian have proven to be exceptionally effective in estimating individual eigenvalues near the edge of the Hamiltonian spectrum, such as the ground state energy. By contrast, evaluating the trace of an operator requires the aggregation of eigenvalues across the entire spectrum. In this work, we introduce an efficient near-term quantum algorithm for computing the trace of a broad class of operators, including matrix functions of the target Hamiltonian. Our trace estimator is similar to the classical Girard-Hutchinson estimator in that it involves the preparation of many random states. Although the exact Girard-Hutchinson estimator is not tractably realizable on a quantum computer, we can construct random states that match the variance of the Girard-Hutchinson estimator through only real-time evolution. Importantly, our random states are all generated using the same Hamiltonians for real-time evolution, with randomness owing only to stochastic variations in the duration of the evolutions. In this sense, the circuit is reconfigurable and suitable for realization on both digital and analog platforms. For numerical illustration, we highlight important applications in the physical, chemical, and materials sciences, such as calculations of density of states and free energy.


# Summary. An optional shortened abstract.
summary: In this paper, we explore the use of real-time evolution for computing the trace of a broad class of operators, including matrix functions of the target Hamiltonian.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://arxiv.org/pdf/2401.04176.pdf'
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
  caption: 'Resolution of identity constructed with quantum Hutchinson states.'
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
