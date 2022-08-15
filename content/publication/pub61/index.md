---
title: 'Implicit hybridized discontinuous Galerkin methods for compressible magnetohydrodynamics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - C. Ciuca
  - P. Fernandez
  - A. Christophe
  - admin
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcpx.2019.100042'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics X
publication_short: Journal of Computational Physics X 5, 100042

abstract: We present hybridized discontinuous Galerkin (HDG) methods for ideal and resistive compressible magnetohydrodynamics (MHD). The HDG methods are fully implicit, high-order accurate and endowed with a unique feature which distinguishes themselves from other discontinuous Galerkin (DG) methods. In particular, they reduce the globally coupled unknowns to the approximate trace of the solution on element boundaries, thereby resulting in considerably smaller global degrees of freedom than other DG methods. Furthermore, we develop a shock capturing method to deal with shocks by appropriately adding artificial bulk viscosity, molecular viscosity, thermal conductivity, and electric resistivity to the physical viscosities in the MHD equations. We show the optimal convergence of the HDG methods for ideal MHD problems and validate our resistive implementation for a magnetic reconnection problem. For smooth problems, we observe that employing a generalized Lagrange multiplier (GLM) formulation can reduce the errors in the divergence of the magnetic field by two orders of magnitude. We demonstrate the robustness of our shock capturing method on a number of test cases and compare our results, both qualitatively and quantitatively, with other MHD solvers. For shock problems, we observe that an effective treatment of both the shock wave and the divergence-free constraint is crucial to ensuring numerical stability.

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
