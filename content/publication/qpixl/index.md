---
title: "Quantum pixel representations and compression for N-dimensional images"
authors:
- Mercy G. Amankwah
- daan-camps
- E. Wes Bethel
- roel-vanbeeumen
- Talita Perciano
date: "2022-05-11T00:00:00Z"
doi: "10.1038/s41598-022-11024-y"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Scientific Reports, 12, Article number: 7712 (2022) "
publication_short: ""

abstract: We introduce a novel and uniform framework for quantum pixel representations that overarches many of the most popular representations proposed in the recent literature, such as (I)FRQI, (I)NEQR, MCRQI, and (I)NCQI. The proposed QPIXL framework results in more efficient circuit implementations and significantly reduces the gate complexity for all considered quantum pixel representations. Our method only requires a linear number of gates in terms of the number of pixels and does not use ancilla qubits. Furthermore, the circuits only consist of Ry gates and CNOT gates making them practical in the NISQ era. Additionally, we propose a circuit and image compression algorithm that is shown to be highly effective, being able to reduce the necessary gates to prepare an FRQI state for example scientific images by up to 90% without sacrificing image quality. Our algorithms are made publicly available as part of QPIXL++, a Quantum Image Pixel Library.

# Summary. An optional shortened abstract.
summary: We introduce a uniform framework for quantum pixel representations that encompasses many of the popular image representations proposed in the literature. We propose a novel circuit implementation with an efficient compression algorithm.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: "https://www.nature.com/articles/s41598-022-11024-y"
url_pdf: 'https://arxiv.org/pdf/2110.04405.pdf'
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
  caption: 'Compressed quantum image representation of scientific data'
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
