---
title: 'An implicit high-order hybridizable discontinuous Galerkin method for the incompressible Navier-Stokes equations'

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

date: '2011-02-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2010.10.032'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 230 (4), 1147-1170

abstract: We present an implicit high-order hybridizable discontinuous Galerkin method for the steady-state and time-dependent incompressible Navier?Stokes equations. The method is devised by using the discontinuous Galerkin discretization for a velocity gradient-pressure?velocity formulation of the incompressible Navier?Stokes equations with a special choice of the numerical traces. The method possesses several unique features which distinguish itself from other discontinuous Galerkin methods. First, it reduces the globally coupled unknowns to the approximate trace of the velocity and the mean of the pressure on element boundaries, thereby leading to a significant reduction in the degrees of freedom. Moreover, if the augmented Lagrangian method is used to solve the linearized system, the globally coupled unknowns become the approximate trace of the velocity only. Second, it provides, for smooth viscous-dominated problems, approximations of the velocity, pressure, and velocity gradient which converge with the optimal order of k + 1 in the L2-norm, when polynomials of degree k?0 are used for all components of the approximate solution. And third, it displays superconvergence properties that allow us to use the above-mentioned optimal convergence properties to define an element-by-element postprocessing scheme to compute a new and better approximate velocity. Indeed, this new approximation is exactly divergence-free, H (div)-conforming, and converges with order k + 2 for k ? 1 and with order 1 for k = 0 in the L2-norm. Moreover, a novel and systematic way is proposed for imposing boundary conditions for the stress, viscous stress, vorticity and pressure which are not naturally associated with the weak formulation of the method. This can be done on different parts of the boundary and does not result in the degradation of the optimal order of convergence properties of the method. Extensive numerical results are presented to demonstrate the convergence and accuracy properties of the method for a wide range of Reynolds numbers and for various polynomial degrees.

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
