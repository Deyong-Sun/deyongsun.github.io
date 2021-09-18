
---
title: "Shape optimization of heterogeneous materials based on isogeometric boundary element method"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chunying Dong

# Author notes (optional)
author_notes:
- "Major contribution"
- "Major contribution"

date: "2021-05-01T00:00:00Z"
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


abstract: In this paper, the isogeometric boundary element method (IGABEM) is used to optimize the shape of heterogeneous materials. In contrast to the isogeometric finite element method (IGAFEM), the iterative optimization algorithm based on IGABEM can be implemented directly from Computer-Aided Design (CAD) without returning the optimization results to CAD designers. The discontinuous element method is extended to IGABEM which deals with corner point problems of inhomogeneous materials. After the singularity of sensitivity analysis of boundary integral equations is demonstrated, the power series expansion method (PSEM) is applied to IGABEM to evaluate various degrees of singularity about sensitivity analysis, which shows more accuracy and efficiency than the element sub-division method (ESDM). A set of control points on the geometric boundary are chosen as design variables, which can be passed from the design model to the analysis model, and the objective function is the elastic energy increment. Finally, several numerical examples in 2D and 3D problems are presented to demonstrate the validity and robustness of the present method.

# Summary. An optional shortened abstract.
summary: Shape optimization.

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
