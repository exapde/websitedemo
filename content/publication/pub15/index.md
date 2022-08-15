---
title: 'Hybridizable discontinuous Galerkin methods for the time-harmonic Maxwells equations'

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
doi: 'https://doi.org/10.1016/j.jcp.2011.05.018'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 230(19), 7151-7175

abstract: We present two hybridizable discontinuous Galerkin (HDG) methods for the numerical solution of the time-harmonic Maxwell?s equations. The first HDG method explicitly enforces the divergence-free condition and thus necessitates the introduction of a Lagrange multiplier. It produces a linear system for the degrees of freedom of the approximate traces of both the tangential component of the vector field and the Lagrange multiplier. The second HDG method does not explicitly enforce the divergence-free condition and thus results in a linear system for the degrees of freedom of the approximate trace of the tangential component of the vector field only. For both HDG methods, the approximate vector field converges with the optimal order of k + 1 in the L2-norm, when polynomials of degree k are used to represent all the approximate variables. We propose elementwise postprocessing to obtain a new Hcurl-conforming approximate vector field which converges with order k + 1 in the Hcurl-norm. We present extensive numerical examples to demonstrate and compare the performance of the HDG methods.

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
