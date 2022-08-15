---
title: 'An implicit high-order hybridizable discontinuous Galerkin method for nonlinear convection-diffusion equations'

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

date: '2009-12-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2009.08.030'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 228 (23), 8841-8855

abstract: In this paper, we present hybridizable discontinuous Galerkin methods for the numerical solution of steady and time-dependent nonlinear convection?diffusion equations. The methods are devised by expressing the approximate scalar variable and corresponding flux in terms of an approximate trace of the scalar variable and then explicitly enforcing the jump condition of the numerical fluxes across the element boundary. Applying the Newton?Raphson procedure and the hybridization technique, we obtain a global equation system solely in terms of the approximate trace of the scalar variable at every Newton iteration. The high number of globally coupled degrees of freedom in the discontinuous Galerkin approximation is therefore significantly reduced. We then extend the method to time-dependent problems by approximating the time derivative by means of backward difference formulae. When the time-marching method is p+1 order accurate and when polynomials of degree p are used to represent the scalar variable, each component of the flux and the approximate trace, we observe that the approximations for the scalar variable and the flux converge with the optimal order of p+1 in the L2 norm. Finally, we apply element-by-element postprocessing schemes to obtain new approximations of the flux and the scalar variable. The new approximate flux, which has a continuous interelement normal component, is shown to converge with order p+1 in the L2 norm. The new approximate scalar variable is shown to converge with order p+2 in the L2 norm. The postprocessing is performed at the element level and is thus much less expensive than the solution procedure. For the time-dependent case, the postprocessing does not need to be applied at each time step but only at the times for which an enhanced solution is required. Extensive numerical results are provided to demonstrate the performance of the present method.

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
