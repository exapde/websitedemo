---
title: 'Scalable parallelization of the hybridized discontinuous Galerkin method for compressible flow'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Xevi Roca
  - admin
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2013-09-01T00:00:00Z'
doi: '10.2514/6.2013-2939'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 21st AIAA Computational Fluid Dynamics Conference
publication_short: 21st AIAA Computational Fluid Dynamics Conference, 2939

abstract: A distributed and parallel implementation of a hybridized discontinuous Galerkin (HDG) solver for the compressible Navier-Stokes equations is presented. This implementation exploits the characteristics of the HDG method. First, the global degrees of freedom are reduced to the numerical trace of the solution on the element boundaries. Second, the conserved quantities and their gradients on each element are obtained in terms of the numerical trace on the element boundary. For meshes composed by a large numer of elements, the cost of the solver is dominated by the first stage, since the second stage scales linearly with the number of elements and it can be parallelized. To accelerate the first stage, we use a distributed GMRES solver with restart pre-conditioned with an algebraic additive Schwarz domain decomposition with l-levels of overlap (ASDD(l)). Each sub-domain problem is approximated by an incomplete LU factorization with k-levels of fill-in (ILU(k)). From the considered tests cases, we conclude that ASDD(1)/ILU(0) presents good weak scaling characteristics for studying the periodic vortex shedding around an airfoil at low Reynolds and low Mach number.

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
