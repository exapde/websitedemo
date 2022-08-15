---
title: 'An implicit high-order hybridizable discontinuous Galerkin method for linear convection-diffusion equations'

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

date: '2009-05-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2009.01.030'

# Schedule page publish date (NOT publication's date).
publishDate: '2009-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 228 (9), 3232-3254

abstract: We present a hybridizable discontinuous Galerkin method for the numerical solution of steady and time-dependent linear convection?diffusion equations. We devise the method as follows. First, we express the approximate scalar variable and corresponding flux within each element in terms of an approximate trace of the scalar variable along the element boundary. We then define a unique value for the approximate trace by enforcing the continuity of the normal component of the flux across the element boundary; a global equation system solely in terms of the approximate trace is thus obtained. The high number of globally coupled degrees of freedom in the discontinuous Galerkin approximation is therefore significantly reduced. If the problem is time-dependent, we discretize the time derivative by means of backward difference formulae. This results in efficient schemes capable of producing high-order accurate solutions in space and time. Indeed, when the time-marching method is th order accurate and when polynomials of degree *p* are used to represent the scalar variable, the flux and the approximate trace, we observe that the approximations for the scalar variable, the flux and the trace of the scalar variable converge with the optimal order of *p+1* in the L2 norm. Finally, we introduce a simple element-by-element postprocessing scheme to obtain new approximations of the flux and the scalar variable. The new approximate flux, which has a continuous inter-element normal component, is shown to converge with order *p+1*. The new approximate scalar variable is shown to converge with order *p+2*. For the time-dependent case, the postprocessing does not need to be applied at each time-step but only at the times for which an enhanced solution is required. Moreover, the postprocessing procedure is less expensive than the solution procedure, since it is performed at the element level. Extensive numerical results are presented to demonstrate the convergence properties of the method.

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
