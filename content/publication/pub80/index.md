---
title: 'An Empirical Interpolation and Model-Variance Reduction Method for Computing Statistical Outputs  of Parametrized Stochastic Partial Differential Equations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - F. Vidal-Codina
  - admin
  - M. B. Giles
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2016-09-01T00:00:00Z'
doi: 'Vidal-Codina, F. and Nguyen, N. C. and Giles, M. B. and Peraire, J.'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: SIAM/ASA Journal on Uncertainty Quantification
publication_short: SIAM/ASA Journal on Uncertainty Quantification 4(1), 244-265

abstract: We present an empirical interpolation and model-variance reduction method for the fast and reliable computation of statistical outputs of parametrized stochastic elliptic partial differential equations. Our method consists of three main ingredients (1) the real-time computation of reduced basis (RB) outputs approximating high-fidelity outputs computed with the hybridizable discontinuous Galerkin (HDG) discretization; (2) the empirical interpolation for an efficient offline-online decoupling of the parametric and stochastic influence; and (3) a multilevel variance reduction method that exploits the statistical correlation between the low-fidelity approximations and the high-fidelity HDG discretization to accelerate the convergence of the Monte Carlo simulations. The multilevel variance reduction method provides efficient computation of the statistical outputs by shifting most of the computational burden from the high-fidelity HDG approximation to the RB approximations. Furthermore, we develop a posteriori error estimates for our approximations of the statistical outputs. Based on these error estimates, we propose an algorithm for optimally choosing both the dimensions of the RB approximations and the size of Monte Carlo samples to achieve a given error tolerance. In addition, we extend the method to compute estimates for the gradients of the statistical outputs. The proposed method is particularly useful for stochastic optimization problems where many evaluations of the objective function and its gradient are required. 

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
