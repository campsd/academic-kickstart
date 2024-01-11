---
title: "Algebraic Compression of Free Fermionic Quantum Circuits: Particle Creation, Arbitrary Lattices and Controlled Evolution"
authors:
- efekan-kokcu
- daan-camps
- lbo
- bert-dejong
- roel-vanbeeumen
- lex-kemper
date: "2023-03-16T00:00:00Z"
doi: "10.48550/arXiv.2303.09538"

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

abstract: Recently we developed a local and constructive algorithm based on Lie algebraic methods for compressing Trotterized evolution under Hamiltonians that can be mapped to free fermions. The compression algorithm yields a circuit which scales linearly in the number of qubits, is fixed depth for for arbitrarily long evolution times and is applicable to time dependent Hamiltonians, although is limited to simple nearest-neighbor spin interactions and fermionic hopping. In this work, we extend the algorithm to compress circuits simulating evolution with long-range spin interactions and fermionic hopping, thereby enabling embedding of arbitrary lattices onto a chain of qubits. Moreover, we show that controlled time evolution, as well as fermion creation and annihilation operators can also be compressed. We demonstrate our results by adiabatically preparing the ground state for a half-filled fermionic chain, and simulating a 4×4 tight binding model on ibmq_washington. With these new developments, our results enable the simulation of a wider range of models of interest and the efficient compression of subcircuits.

# Summary. An optional shortened abstract.
summary: We extend our circuit compression algorithms to free fermionic systems on arbitrary lattices, incorporate particle creation operations, and allow for controlled evolution.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://arxiv.org/pdf/2303.09538.pdf'
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
  caption: 'QPU versus simulator results of a fermion undergoing ballistic transport on a 4 x 4 lattice.'
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
