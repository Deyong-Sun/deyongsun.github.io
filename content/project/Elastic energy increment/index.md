
---
title: Isogeometric Boundary Element Method for Viscoelastic Effects of Solid Propellant
summary: Isogeometric Boundary Element Method for Turbine Blade Failure in Aeroengines
tags:
- Demo
date: "2018-06-2019-03"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Deformed processes
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/StevenS68197468
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
Steps:

* Rebuilt 2D NACA airfoil geometries by NURBS using Matlab
* Implemented Galerkin boundary element method to calculate the potential problem
* Used Lagrange multiplier to deal with Kutta condition in coefficient matrix
* Simulated the fluid-structure coupled behavior of turbine blades
* Compared numerical results with that from traditional panel method and Xfoil
