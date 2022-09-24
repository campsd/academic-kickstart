---
title: "FABLE: Fast Approximate Quantum Circuits for Block-Encodings"
authors:
- daan-camps
- roel-vanbeeumen
date: "2022-09-23T00:00:00Z"
doi: "10.1109/QCE53715.2022.00029"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE International Conference on Quantum Computing and Engineering (QCE)"
publication_short: "IEEE QCE22"

abstract: Block-encodings of matrices have become an essential element of quantum algorithms derived from the quantum singular value transformation. This includes a variety of algorithms ranging from the quantum linear systems problem to quantum walk, Hamiltonian simulation, and quantum machine learning. Many of these algorithms achieve optimal complexity in terms of black box matrix oracle queries, but so far the problem of computing quantum circuit implementations for block-encodings of matrices has been under-appreciated. In this paper we propose FABLE, a method to generate approximate quantum circuits for block-encodings of matrices in a fast manner. FABLE circuits have a simple structure and are directly formulated in terms of one- and two-qubit gates. For small and structured matrices they are feasible in the NISQ era, and the circuit parameters can be easily generated for problems up to fifteen qubits. Furthermore, we show that FABLE circuits can be compressed and sparsified. We provide a compression theorem that relates the compression threshold to the error on the block-encoding. We benchmark our method for Heisenberg and Hubbard Hamiltonians, and Laplacian operators to illustrate that they can be implemented with a reduced gate complexity without approximation error.

# Summary. An optional shortened abstract.
summary: Fast synthesis of quantum circuits for approximate block-encodings.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: "arxiv.org/abs/2007.01417"
url_pdf: 'https://arxiv.org/pdf/2205.00081.pdf'
url_code: 'https://github.com/QuantumComputingLab/fable'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Gate complexities for block encoding 1D and 2D Laplacians'
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
