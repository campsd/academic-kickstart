---
title: "An Algebraic Quantum Circuit Compression Algorithm for Hamiltonian Simulation"
authors:
- daan-camps
- Efekan Kokcu
- Lindsay Bassman
- Wibe A. de Jong
- Alexander F. Kemper
- roel-vanbeeumen
date: "2021-08-09T00:00:00Z"
doi: "10.1137/21M1439298"

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

abstract: Quantum computing is a promising technology that harnesses the peculiarities of quantum mechanics to deliver computational speedups for some problems that are intractable to solve on a classical computer. Current generation noisy intermediate-scale quantum (NISQ) computers are severely limited in terms of chip size and error rates. Shallow quantum circuits with uncomplicated topologies are essential for successful applications in the NISQ era. Based on matrix analysis, we show that Hamiltonian simulation of certain spin models known as free fermions can be performed in a quantum circuit with a depth that is independent of simulation time and that grows linearly in the number of spins. Our analysis shows how to efficiently and accurately compress these circuits with a numerical algorithm that scales cubically in the number of spins. Numerical experiments show that our circuit synthesis algorithm easily scales up to $O(10^3)$ spins. The resulting quantum circuits have a simple nearest-neighbor topology, which makes them ideally suited for NISQ devices.

# Summary. An optional shortened abstract.
summary: We present a numerical algorithm for compressing quantum circuits related to Hamiltonian simulation.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: "arxiv.org/abs/2007.01417"
url_pdf: 'https://arxiv.org/pdf/2108.03283.pdf'
url_code: 'https://github.com/QuantumComputingLab'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Timings for circuit compression algorithms for XY and TFXY Hamiltonians'
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
