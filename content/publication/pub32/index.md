---
title: 'A high-order hybridizable discontinuous Galerkin method for elliptic interface problems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - LNT Huynh
  - admin
  - J Peraire
  - BC Khoo

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2013-09-01T00:00:00Z'
doi: 'https://doi.org/10.1002/nme.4382'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: International Journal for Numerical Methods in Engineering
publication_short: International Journal for Numerical Methods in Engineering 93(2), 183-200

abstract: We present a high-order hybridizable discontinuous Galerkin method for solving elliptic interface problems in which the solution and gradient are nonsmooth because of jump conditions across the interface. The hybridizable discontinuous Galerkin method is endowed with several distinct characteristics. First, they reduce the globally coupled unknowns to the approximate trace of the solution on element boundaries, thereby leading to a significant reduction in the global degrees of freedom. Second, they provide, for elliptic problems with polygonal interfaces, approximations of all the variables that converge with the optimal order of k?+?1 in the L2(?)-norm where k denotes the polynomial order of the approximation spaces. Third, they possess some superconvergence properties that allow the use of an inexpensive element-by-element postprocessing to compute a new approximate solution that converges with order k?+?2. However, for elliptic problems with finite jumps in the solution across the curvilinear interface, the approximate solution and gradient do not converge optimally if the elements at the interface are isoparametric. The discrepancy between the exact geometry and the approximate triangulation near the curved interfaces results in lower order convergence. To recover the optimal convergence for the approximate solution and gradient, we propose to use superparametric elements at the interface.

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
