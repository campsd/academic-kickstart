---
title: "QCLAB++: Simulating Quantum Circuits on GPUs"
authors:
- roel-vanbeeumen
- daan-camps
- Neil Mehta
date: "2023-02-28T00:00:00Z"
doi: "10.48550/arXiv.2303.00123"

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

abstract: We introduce qclab++, a light-weight, fully-templated C++ package for GPU-accelerated quantum circuit simulations. The code offers a high degree of portability as it has no external dependencies and the GPU kernels are generated through OpenMP offloading. qclab++ is designed for performance and numerical stability through highly optimized gate simulation algorithms for 1-qubit, controlled 1-qubit, and 2-qubit gates. Furthermore, we also introduce qclab, a quantum circuit toolbox for Matlab with a syntax that mimics qclab++. This provides users the flexibility and ease of use of a scripting language like Matlab for studying their quantum algorithms, while offering high-performance GPU acceleration when required. As such, the qclab++ library offers a unique combination of features. We compare the CPU simulator in qclab++ with the GPU kernels generated by OpenMP and observe a speedup of over 40×. Furthermore, we also compare qclab++ to other circuit simulation packages, such as cirq-qsim and qibo, in a series of benchmarks conducted on NERSC's Perlmutter system and illustrate its competitiveness.

# Summary. An optional shortened abstract.
summary: We report a series benchmarks conducted in NERSC's Perlmutter system using a GPU adaptation of QCLAB++, a light-weight, fully-templated C++ package for quantum circuit simulations. 

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://arxiv.org/pdf/2303.00123.pdf'
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
  caption: 'Speedup factor of GPU versus CPU simulation of a Hamiltonian evolution circuit.'
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
