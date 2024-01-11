---
title: "Algebraic Compression of Quantum Circuits for Hamiltonian Evolution"
authors:
- efekan-kokcu
- daan-camps
- lbo
- J. K. Freericks
- bert-dejong
- roel-vanbeeumen
- lex-kemper
date: "2022-03-10T00:00:00Z"
doi: "10.1103/PhysRevA.105.032420"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Physical Review A 105, 032420"
publication_short: "Phys. Rev. A 105, 032420"

abstract: Unitary evolution under a time dependent Hamiltonian is a key component of simulation on quantum hardware. Synthesizing the corresponding quantum circuit is typically done by breaking the evolution into small time steps, also known as Trotterization, which leads to circuits whose depth scales with the number of steps. When the circuit elements are limited to a subset of SU(4) — or equivalently, when the Hamiltonian may be mapped onto free fermionic models — several identities exist that combine and simplify the circuit. Based on this, we present an algorithm that compresses the Trotter steps into a single block of quantum gates. This results in a fixed depth time evolution for certain classes of Hamiltonians. We explicitly show how this algorithm works for several spin models, and demonstrate its use for adiabatic state preparation of the transverse field Ising model.

# Summary. An optional shortened abstract.
summary: By analyzing the Hamiltonian algebra, we show that Trotter circuits for simulation of free fermions are efficiently compressible. Our method is applied to an adiabatic state preparation experiment.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
url_pdf: 'https://arxiv.org/pdf/2108.03282.pdf'
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
  caption: 'Adiabatic state preparation of a TFIM Hamiltonian on quantum hardware'
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
