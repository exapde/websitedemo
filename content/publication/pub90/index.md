---
title: 'A multiscale continuous Galerkin method for stochastic simulation and robust design of photonic crystals'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - F. Vidal-Codina
  - J. Saa-Seoane
  - admin
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2019-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcpx.2019.100016'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics X
publication_short: Journal of Computational Physics X 2, 100016

abstract: We present a multiscale continuous Galerkin (MSCG) method for the fast and accurate stochastic simulation and optimization of time-harmonic wave propagation through photonic crystals. The MSCG method exploits repeated patterns in the geometry to drastically decrease computational cost and incorporates the following ingredients (1) a reference domain formulation that allows us to treat geometric variability resulting from manufacturing uncertainties; (2) a reduced basis approximation to solve the parametrized local subproblems; (3) a gradient computation of the objective function; and (4) a model and variance reduction technique that enables the accelerated computation of statistical outputs by exploiting the statistical correlation between the MSCG solution and the reduced basis approximation. The proposed method is thus well suited for both deterministic and stochastic simulations, as well as robust design of photonic crystals. We provide convergence and cost analysis of the MSCG method, as well as a simulation results for a waveguide T-splitter and a Z-bend to illustrate its advantages for stochastic simulation and robust design.

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
