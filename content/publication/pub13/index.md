---
title: 'High-order implicit hybridizable discontinuous Galerkin methods for acoustics and elastodynamics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin
  - Jaume Peraire
  - Bernardo Cockburn

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2011-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2011.01.035'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 230(10), 3695-3718

abstract: We present a class of hybridizable discontinuous Galerkin (HDG) methods for the numerical simulation of wave phenomena in acoustics and elastodynamics. The methods are fully implicit and high-order accurate in both space and time, yet computationally attractive owing to their following distinctive features. First, they reduce the globally coupled unknowns to the approximate trace of the velocity, which is defined on the element faces and single-valued, thereby leading to a significant saving in the computational cost. In addition, all the approximate variables (including the approximate velocity and gradient) converge with the optimal order of k + 1 in the L2-norm, when polynomials of degree k ? 0 are used to represent the numerical solution and when the time-stepping method is accurate with order k + 1. When the time-stepping method is of order k + 2, superconvergence properties allows us, by means of local postprocessing, to obtain better, yet inexpensive approximations of the displacement and velocity at any time levels for which an enhanced accuracy is required. In particular, the new approximations converge with order k + 2 in the L2-norm when k ? 1 for both acoustics and elastodynamics. Extensive numerical results are provided to illustrate these distinctive features.

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
