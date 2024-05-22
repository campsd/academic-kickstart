---
title: "Evaluation of the Classical Hardware Requirements for Large-Scale Quantum Computations"
event: ISC High Performance 2024
event_url: https://www.isc-hpc.com/

location: ISC24 - Hamburg, Germany
address:
  street: 
  city: Hamburg
  region: 
  postcode: ''
  country: Germany

summary: Presentation on a performance model for large-scale quantum computations at ISC High Performance 2024 in Hamburg.
abstract: "We develop a new model to evaluate the necessary classical computing and networking resources required to support a large-scale fault-tolerant quantum computer based on superconducting qubits and a surface code architecture. We focus specifically on quantum error decoding, which is the main classical computational task required to enable quantum error correction during runtime. Our model reveals that the quantum computer operates at a logical clock speed in the 100-10,000 Hz range, using state-of-the-art quantum error decoders. For a prototypical large-scale quantum chemistry computation, this translates to an overall runtime on the order of months, and this workload is estimated to generate syndrome data for error correction at a rate of 2–500 Gbps depending on whether data compression is used. We estimate the total computational processing power required for online error syndrome decoding equals about 1 petaflop. The results of our analysis show that current computing and networking technology can meet the requirements, in terms of bandwidth, latency, and compute, to support large-scale quantum computation. However, major technological challenges remain both for quantum and classical hardware, including scalable fabrication of high-quality qubits, scalable qubit control, and syndrome communication within a limited power budget."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2024-05-13T16:15:00Z"
#date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2019-11-01T00:00:00Z"

authors:
- daan-camps
tags:
- Quantum Computing

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Estimate of the compute intensity in function of the number of logical qubits and T-depth.'
  focal_point: Right

links:
url_code: "https://zenodo.org/records/10818960"
url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10528937"
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:


# Enable math on this page?
math: true
---

This work won the [Hans Meuer best research paper award](https://www.isc-hpc.com/press-releases/lbnl-researchers-bag-2024-hans-meuer-award-for-work-on-quantum-computations.html).
