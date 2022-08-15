---
title: 'Bandgap optimization of two-dimensional photonic crystals using semidefinite programming and subspace methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Han Men
  - admin
  - Robert M Freund
  - Pablo A Parrilo
  - Jaume Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2010-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2010.01.023'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 229(10), 3706-3725

abstract: In this paper, we consider the optimal design of photonic crystal structures for two-dimensional square lattices. The mathematical formulation of the bandgap optimization problem leads to an infinite-dimensional Hermitian eigenvalue optimization problem parametrized by the dielectric material and the wave vector. To make the problem tractable, the original eigenvalue problem is discretized using the finite element method into a series of finite-dimensional eigenvalue problems for multiple values of the wave vector parameter. The resulting optimization problem is large-scale and non-convex, with low regularity and non-differentiable objective. By restricting to appropriate eigenspaces, we reduce the large-scale non-convex optimization problem via reparametrization to a sequence of small-scale convex semidefinite programs (SDPs) for which modern SDP solvers can be efficiently applied. Numerical results are presented for both transverse magnetic (TM) and transverse electric (TE) polarizations at several frequency bands. The optimized structures exhibit patterns which go far beyond typical physical intuition on periodic media design.

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
