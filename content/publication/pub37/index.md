---
title: 'An embedded discontinuous Galerkin method for the compressible Euler and Navier-Stokes equations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Jaime Peraire
  - admin
  - Bernardo Cockburn

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2011-09-01T00:00:00Z'
doi: 'https://doi.org/10.2514/6.2011-3228'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 20th AIAA Computational Fluid Dynamics Conference
publication_short: 20th AIAA Computational Fluid Dynamics Conference, 3228

abstract: We present an Embedded Discontinuous Galerkin (EDG) method for the solution of the compressible Euler and Navier-Stokes equations. The method is devised by using the discontinuous Galerkin approximation with a special choice of the numerical fluxes and weakly imposing the continuity of the normal component of the numerical fluxes across the element interfaces. This allows the approximate conserved variables defining the discontinuous Galerkin solution to be locally condensed, thereby resulting in a reduced system which involves only the degrees of freedom of the approximate traces of the solution. The EDG method can be seen as a particular form of a Hybridizable Discontinuous Galerkin (HDG) method in which the hybrid fluxes are required to belong to a smaller space than in standard HDG methods. In our EDG method, the hybrid unknown is taken to be continuous at the vertices, thus resulting in an even smaller number of coupled degrees of freedom than in the HDG method. In fact, the resulting stiffness matrix has the same structure as that of the statically condensed continuous Galerkin method. In exchange for the reduced number of degrees of freedom, the EDG method looses the optimal converge property of the flux which characterizes other HDG methods. Thus, for convection-diffusion problems, the EDG solution converges optimally for the primal unknown but suboptimally for the flux.

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
