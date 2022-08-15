---
title: 'RANS solutions using high order discontinuous Galerkin methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin
  - Per-Olof Persson
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2007-09-01T00:00:00Z'
doi: 'https://doi.org/10.2514/6.2007-914'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 45th AIAA Aerospace Sciences Meeting and Exhibit
publication_short: 45th AIAA Aerospace Sciences Meeting and Exhibit, 914

abstract: We present a practical approach for the numerical solution of the Reynolds averaged Navier-Stokes (RANS) equations using high-order discontinuous Galerkin methods. Turbulence is modeled by the Spalart-Allmaras (SA) one-equation model. We introduce an artificial viscosity model for SA equation which is aimed at accommodating high-order RANS approximations on grids which would otherwise be too coarse. Generally, the model term is only active at the edge of the boundary layer, where the grid resolution is insufficient to capture the abrupt change in curvature required for the eddy viscosity profile to match its free-stream value. Furthermore, the amount of viscosity required decreases with the grid resolution and vanishes when the resolution is sufficiently high. For transonic computations, an additional shock-capturing artificial viscosity model term is required. Numerical predictions for turbulent flows past a flat plate and a NACA 0012 airfoil are presented via comparison with the experimental measurements. In the flat plate case, grid refinement studies are performed in order to assess the convergence properties and demonstrate the effectiveness of high-order approximations.

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
