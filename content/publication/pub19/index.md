---
title: 'An efficient reduced-order modeling approach for non-linear parametrized partial differential equations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2008-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: International Journal for Numerical Methods in Engineering
publication_short: International Journal for Numerical Methods in Engineering 76(1), 27-55

abstract: We present hybridizable discontinuous Galerkin methods for solving steady and time-dependent partial differential equations (PDEs) in continuum mechanics. The essential ingredients are a local Galerkin projection of the underlying PDEs at the element level onto spaces of polynomials of degree k to parametrize the numerical solution in terms of the numerical trace; a judicious choice of the numerical flux to provide stability and consistency; and a global jump condition that enforces the continuity of the numerical flux to arrive at a global weak formulation in terms of the numerical trace. The HDG methods are fully implicit, high-order accurate and endowed with several unique features which distinguish themselves from other discontinuous Galerkin methods. First, they reduce the globally coupled unknowns to the approximate trace of the solution on element boundaries, thereby leading to a significant reduction in the degrees of freedom. Second, they provide, for smooth viscous-dominated problems, approximations of all the variables which converge with the optimal order of k + 1 in the L2-norm. Third, they possess some superconvergence properties that allow us to define inexpensive element-by-element postprocessing procedures to compute a new approximate solution which may converge with higher order than the original solution. And fourth, they allow for a novel and systematic way for imposing boundary conditions for the total stress, viscous stress, vorticity and pressure which are not naturally associated with the weak formulation of the methods. In addition, they possess other interesting properties for specific problems. Their approximate solution can be postprocessed to yield an exactly divergence-free and H(div)-conforming velocity field for incompressible flows. They do not exhibit volumetric locking for nearly incompressible solids. We provide extensive numerical results to illustrate their distinct characteristics and compare their performance with that of continuous Galerkin methods.

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
