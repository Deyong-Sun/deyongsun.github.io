---
title: "_RI-IGABEM_ for 2D viscoelastic problems and its application to solid propellant grains"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rui Dai
- Xiangyang Liu
- Yusheng Zhan
- Chunying Dong

# Author notes (optional)
author_notes:
- "Major contribution"
- "Minor contribution"
- "Minor contribution"
- "Minor contribution"
- "Major contribution"

date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Methods in Applied Mechanics and Engineering*
publication_short: In *CMAME*

abstract: The isogeometric boundary element method (IGABEM) has a broad application prospect due to its exact geometric representation, excellent field approximation and only boundary discretization property. In this paper, IGABEM based on radial integration method (RI\-IGABEM) is used for viscoelastic analysis of solid propellant grain. The memory stress, as the initial stress, leads to the boundary-domain integral equations and thus eliminates the only boundary discretization advantage of boundary element method (BEM). The radial integration method (RIM) is applied to transform the domain integral into an equivalent boundary integral by means of the applied points. The usage of RIM makes it possible to only store the strains on the applied points. Meanwhile, Prony-series is used to discretize the general integrals and to store the two most recent time-step strains rather than the time-step strains of the entire process. The combination between RIM and Prony-series will help reduce the storage space and computational time. In addition, by using the fundamental solutions for linear elastic problems and the regularized technologies, the singular integrals can be solved through the previous methods, such as the Telles scheme and element sub-division method. In order to validate the accuracy and robustness of RI-IGABEM in viscoelastic analysis, the influence of the number and position of applied points as well as the time interval on viscoelastic analysis is discussed through comparing with cell discretization methods. A set of numerical examples demonstrates the ability of the scheme to simulate the viscoelastic problems.

# Summary. An optional shortened abstract.
summary: Viscoelastic analysis.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
