---
title: "Diagrammatic Quantum Circuit Compression for Hamiltonian Simulation"
authors:
- Victoria Wadewitz
- Aaron Szasz
- daan-camps
- katie-klymko
- Tobias Stollenwerk


date: "2025-02-01T00:00:00Z"
doi: "10.18420/se2025-ws-24"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Software Engineering 2025 – Companion Proceedings"
publication_short: ""

abstract: One of the promising applications for early quantum computers is the simulation of of dynamical quantum systems. Due to the limited coherence time of such devices, the depth-compression of quantum circuits is crucial to facilitate useful results. It has been shown that certain quantum models can even be compressed to constant depth, meaning it is only linearly dependent on the number of qubits, but independent of the simulation time and the number of Trotter steps. This has been done by extracting the circuit structure derived from the model characteristics via Hamiltonian simulation. Based on these results, we present a diagrammatic approach to circuit compression utilizing a powerful technique for reasoning about quantum circuits called ZX-calculus. We demonstrate our approach by deriving constant-depth circuit compressions for quantum models known to be constant-depth, as well as novel models previously unstudied. Our method could serve as a first step toward the development of more advanced circuit compression methods, that could be employed to enable Hamiltonian simulation of a larger variety of quantum models, and beyond.

# Summary. An optional shortened abstract.
summary: We derive the results on compression of Hamiltonian simulation circuits using ZX-calculus.

tags:
- Quantum Computing
featured: false

# links:
# - name: ""
#url: ""
url_pdf: 'https://dl.gi.de/server/api/core/bitstreams/d8f62c84-d53c-4726-9d69-9a47635d6657/content'
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
  caption: 'The compression rules can be derived using phase gadgets from ZX-calculus.'
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
