---
title: 'A class of embedded discontinuous Galerkin methods for computational fluid dynamics'

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

date: '2015-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2015.09.024'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 302, 674-692

abstract: We present a class of embedded discontinuous Galerkin (EDG) methods for numerically solving the Euler equations and the Navier?Stokes equations. The essential ingredients are a local Galerkin projection of the underlying governing equations at the element level onto spaces of polynomials of degree k to parametrize the numerical solution in terms of the approximate trace, a judicious choice of the numerical flux to provide stability and consistency, and a global jump condition that weakly enforces the single-valuedness of the numerical flux to arrive at a global formulation in terms of the numerical trace. The EDG methods are thus obtained from the hybridizable discontinuous Galerkin (HDG) method by requiring the approximate trace to belong to smaller approximation spaces than the one in the HDG method. In the EDG methods, the numerical trace is taken to be continuous on a suitable collection of faces, thus resulting in an even smaller number of globally coupled degrees of freedom than in the HDG method. On the other hand, the EDG methods are no longer locally conservative. In the framework of convection?diffusion problems, this lack of local conservativity is reflected in the fact that the EDG methods do not provide the optimal convergence of the approximate gradient or the superconvergence for the scalar variable for diffusion-dominated problems as the HDG method does. However, since the HDG method does not display these properties in the convection-dominated regime, the EDG method becomes a reasonable alternative since it produces smaller algebraic systems than the HDG method. In fact, the resulting stiffness matrix has a similar sparsity pattern as that of the statically condensed continuous Galerkin (CG) method. The main advantage of the EDG methods is that they are generally more stable and robust than the CG method for solving convection-dominated problems. Numerical results are presented to illustrate the performance of the EDG methods. They confirm that, even though the EDG methods are not locally conservative, they are a viable alternative to the HDG method in the convection-dominated regime.

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
