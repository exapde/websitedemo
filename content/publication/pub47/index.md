---
title: 'A phase-based hybridizable discontinuous Galerkin method for the numerical solution of the Helmholtz equation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin
  - J. Peraire
  - F. Reitich
  - B. Cockburn

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2015-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2015.02.002'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 290, 318-335

abstract: We introduce a new hybridizable discontinuous Galerkin (HDG) method for the numerical solution of the Helmholtz equation over a wide range of wave frequencies. Our approach combines the HDG methodology with geometrical optics in a fashion that allows us to take advantage of the strengths of these two methodologies. The phase-based HDG method is devised as follows. First, we enrich the local approximation spaces with precomputed phases which are solutions of the eikonal equation in geometrical optics. Second, we propose a novel scheme that combines the HDG method with ray tracing to compute multivalued solution of the eikonal equation. Third, we utilize the proper orthogonal decomposition to remove redundant modes and obtain locally orthogonal basis functions which are then used to construct the global approximation spaces of the phase-based HDG method. And fourth, we propose an appropriate choice of the stabilization parameter to guarantee stability and accuracy for the proposed method. Numerical experiments presented show that optimal orders of convergence are achieved, that the number of degrees of freedom to achieve a given accuracy is independent of the wave number, and that the number of unknowns required to achieve a given accuracy with the proposed method is orders of magnitude smaller than that with the standard finite element method.

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
