---
title: ILAS 2017
event: ILAS 2017
event_url: https://ilas2017.math.iastate.edu

location: Iowa State University, Ames
address:
  street: 
  city: 
  region: 
  postcode: ''
  country:

summary: Abstract and slides for ILAS 2017 talk.
abstract: "Krylov subspace methods are frequently used throughout scientific computing. In this talk we focus on the rational Krylov method which is used, among others, for the (non)linear eigenvalue problem, rational approximation, and contour integration. Implicit restarting is often necessary and relies on applying QR steps on the recurrence matrices. Classically this is done by the explicit QR algorithm, not exploiting any structure of the recurrence matrices involved. Though theoretically fine, these explicit steps are costly and can exhibit numerical difficulties. We will present a new approach using an implicit, structure preserving QR algorithm to overcome the classical drawbacks. To achieve this we apply an initial unitary transformation on the rational Krylov pencil that acts directly on a QR factored form of the recurrence matrices. This transformation allows for the application of a generalized implicit QZ step on the rational Krylov pencil that naturally preserves the structure in the recurrence matrices. This proves to be an efficient framework for the formulation of the implicit restart of the rational Krylov method or, equivalently, for the application of a rational filter. It has multiple advantages over traditional approaches: complex conjugate Ritz pairs can be removed from real pencils in real arithmetic, the structure is preserved
throughout the algorithm such that the subspace can be easily expanded after the contraction phase, and deflation of Ritz values can be carefully monitored.
We illustrate the viability of the new algorithm with some numerical examples."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2017-07-27T12:00:00Z"
#date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2019-11-01T00:00:00Z"

authors:
- admin
tags:


# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Rational filter applied to starting vector'
  focal_point: Right

links:
url_code: ""
url_pdf: ""
url_slides: "files/talks/ILAS17.pdf"
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
