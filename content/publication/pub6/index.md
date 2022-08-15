---
title: 'A hybridizable discontinuous Galerkin method for Stokes flow'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin
  - Jaime Peraire
  - Bernardo Cockburn

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2010-01-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.cma.2009.10.007'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Computer Methods in Applied Mechanics and Engineering 199 (9-12), 582-597

abstract: In this paper, we introduce a hybridizable discontinuous Galerkin method for Stokes flow. The method is devised by using the discontinuous Galerkin methodology to discretize a velocity?pressure?gradient formulation of the Stokes system with appropriate choices of the numerical fluxes and by applying a hybridization technique to the resulting discretization. One of the main features of this approach is that it reduces the globally coupled unknowns to the numerical trace of the velocity and the mean of the pressure on the element boundaries, thereby leading to a significant reduction in the size of the resulting matrix. Moreover, by using an augmented lagrangian method, the globally coupled unknowns are further reduced to the numerical trace of the velocity only. Another important feature is that the approximations of the velocity, pressure, and gradient converge with the optimal order of in the L2 norm, when polynomials of degree k are used to represent the approximate variables. Based on the optimal convergence of the HDG method, we apply an element-by-element postprocessing scheme to obtain a new approximate velocity, which converges with order k+2 in the L2 norm. The postprocessing performed at the element level is less expensive than the solution procedure. Numerical results are provided to assess the performance of the method.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
