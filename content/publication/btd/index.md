---
title: "Block term decomposition for modelling epileptic seizures"
authors:
- Borbala Hunyadi
- admin
- Laurent Sorber
- Wim Van Paesschen
- Maarten De Vos
- Sabine Van Huffel
- Lieven De Lathauwer
date: "2014-09-08T00:00:00Z"
doi: "10.1186/1687-6180-2014-139"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*EURASIP Journal on Advances in Signal Processing*"
publication_short: ""

abstract: Recordings of neural activity, such as EEG, are an inherent mixture of different ongoing brain processes as well as artefacts and are typically characterised by low signal-to-noise ratio. Moreover, EEG datasets are often inherently multidimensional, comprising information in time, along different channels, subjects, trials, etc. Additional information may be conveyed by expanding the signal into even more dimensions, e.g. incorporating spectral features applying wavelet transform. The underlying sources might show differences in each of these modes. Therefore, tensor-based blind source separation techniques which can extract the sources of interest from such multiway arrays, simultaneously exploiting the signal characteristics in all dimensions, have gained increasing interest. Canonical polyadic decomposition (CPD) has been successfully used to extract epileptic seizure activity from wavelet-transformed EEG data (Bioinformatics 23(13):i10–i18, 2007; NeuroImage 37:844–854, 2007), where each source is described by a rank-1 tensor, i.e. by the combination of one particular temporal, spectral and spatial signature. However, in certain scenarios, where the seizure pattern is nonstationary, such a trilinear signal model is insufficient. Here, we present the application of a recently introduced technique, called block term decomposition (BTD) to separate EEG tensors into rank-$(L_r ,L_r ,1)$ terms, allowing to model more variability in the data than what would be possible with CPD. In a simulation study, we investigate the robustness of BTD against noise and different choices of model parameters. Furthermore, we show various real EEG recordings where BTD outperforms CPD in capturing complex seizure characteristics.

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://asp-eurasipjournals.springeropen.com/track/pdf/10.1186/1687-6180-2014-139'
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
  caption: 'Ictal EEG data and its tensor decomposition'
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
