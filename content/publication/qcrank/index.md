---
title: "Quantum-parallel vectorized data encodings and computations on trapped-ions and transmons QPUs"
authors:
- jan-balewski
- Mercy G. Amankwah
- roel-vanbeeumen
- E. Wes Bethel
- Talita Perciano
- daan-camps
date: "2024-02-10T00:00:00Z"
doi: "10.1038/s41598-024-53720-x"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Scientific Reports 14, 3435 (2024)"
publication_short: "Sci Rep 14, 3435 (2024)"

abstract: Compact quantum data representations are essential to the emerging field of quantum algorithms for data analysis. We introduce two new data encoding schemes, QCrank and QBArt, which have a high degree of quantum parallelism through uniformly controlled rotation gates. QCrank encodes a sequence of real-valued data as rotations of the data qubits, allowing for high storage density. QBArt directly embeds a binary representation of the data in the computational basis, requiring fewer quantum measurements and lending itself to well-understood arithmetic operations on binary data. We present several applications of the proposed encodings for different types of data. We demonstrate quantum algorithms for DNA pattern matching, Hamming weight calculation, complex value conjugation, and retrieving an O(400) bits image, all executed on the Quantinuum QPU. Finally, we use various cloud-accessible QPUs, including IBMQ and IonQ, to perform additional benchmarking experiments.

# Summary. An optional shortened abstract.
summary: This paper proposes a nested state preparation circuit construction with a high degree of quantum parallelism. We test this circuit to load a variety of data sets stemming from applications and process them directly on a real QPU.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://arxiv.org/pdf/2301.07841.pdf'
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
  caption: 'Computing the complex conjugate of a complex exponential on the Quantinuum H1-1 QPU'
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
