---
title: 'The hybridized discontinuous Galerkin method for implicit large-eddy simulation of transitional turbulent flows'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:    
  - Pablo Fernandez
  - admin
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2017-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2017.02.015'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 336, 308-329

abstract: We present a high-order Implicit Large-Eddy Simulation (ILES) approach for transitional aerodynamic flows. The approach encompasses a hybridized Discontinuous Galerkin (DG) method for the discretization of the Navier?Stokes (NS) equations, and a parallel preconditioned Newton-GMRES solver for the resulting nonlinear system of equations. The combination of hybridized DG methods with an efficient solution procedure leads to a high-order accurate NS solver that is competitive to alternative approaches, such as finite volume and finite difference codes, in terms of computational cost. The proposed approach is applied to transitional flows over the NACA 65-(18)10 compressor cascade and the Eppler 387 wing at Reynolds numbers up to 460,000. Grid convergence studies are presented and the required resolution to capture transition at different Reynolds numbers is investigated. Numerical results show rapid convergence and excellent agreement with experimental data. In short, this work aims to demonstrate the potential of high-order ILES for simulating transitional aerodynamic flows. This is illustrated through numerical results and supported by theoretical considerations.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
#  - name: Link
#    url: https://link.springer.com/article/10.1007/s11831-010-9056-z

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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - cesmix

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to import publication metadata into your reference management software.
{{% /callout %}}
