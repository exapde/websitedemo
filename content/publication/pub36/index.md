---
title: 'A hybridizable discontinuous Galerkin method for the incompressible Navier-Stokes equations'

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

date: '2010-09-01T00:00:00Z'
doi: 'https://doi.org/10.2514/6.2010-362'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 48th AIAA Aerospace Sciences meeting including the new horizons forum and aerospace exposition
publication_short: 48th AIAA Aerospace Sciences meeting including the new horizons forum and aerospace exposition, 362

abstract: We present a hybridizable discontinuous Galerkin method for the numerical solution the incompressible Navier-Stokes equations. The method is devised by using the discontinuous Galerkin approximation with a special choice of the numerical traces and a fully implicit time-stepping method for temporal discretization. The HDG method possesses several unique features which distinguish themselves from other discontinuous Galerkin methods. First, it reduces the globally coupled unknowns to the approximate trace of the velocity and the mean of the pressure on element boundaries, thereby leading to a significant reduction in the degrees of freedom. Second, it allows for pressure, vorticity and stress boundary conditions to be prescribed on different parts of the boundary. Third, it provides, for smooth viscous-dominated problems, approximations of the velocity, pressure, and velocity gradient which converge with the optimal order of k+1 in the L2 norm, when polynomials of degree k ? 0 are used for all components of the approximate solution. And fourth, it displays superconvergence properties that allow us to use the above-mentioned optimal convergence properties to define an element-by-element postprocessing scheme to compute a new and better approximate velocity. Indeed, this new approximation is exactly divergence-free, H(div)-conforming, and converges with order k + 2 for k ? 1 and with order 1 for k = 0 in the L2 norm. We present extensive numerical results to demonstrate the accuracy and convergence properties of the method for a wide range of Reynolds numbers and for various polynomial degrees.

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
