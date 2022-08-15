---
title: 'A model and variance reduction method for computing statistical outputs of stochastic elliptic partial differential equations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - F. Vidal-Codina
  - admin
  - M.B. Giles
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2015-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2015.05.041'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 297, 700-720

abstract: We present a model and variance reduction method for the fast and reliable computation of statistical outputs of stochastic elliptic partial differential equations. Our method consists of three main ingredients (1) the hybridizable discontinuous Galerkin (HDG) discretization of elliptic partial differential equations (PDEs), which allows us to obtain high-order accurate solutions of the governing PDE; (2) the reduced basis method for a new HDG discretization of the underlying PDE to enable real-time solution of the parameterized PDE in the presence of stochastic parameters; and (3) a multilevel variance reduction method that exploits the statistical correlation among the different reduced basis approximations and the high-fidelity HDG discretization to accelerate the convergence of the Monte Carlo simulations. The multilevel variance reduction method provides efficient computation of the statistical outputs by shifting most of the computational burden from the high-fidelity HDG approximation to the reduced basis approximations. Furthermore, we develop a posteriori error estimates for our approximations of the statistical outputs. Based on these error estimates, we propose an algorithm for optimally choosing both the dimensions of the reduced basis approximations and the sizes of Monte Carlo samples to achieve a given error tolerance. We provide numerical examples to demonstrate the performance of the proposed method.

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