---
title: 'Symplectic Hamiltonian HDG methods for wave propagation phenomena'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - M. A. Sanchez
  - C. Ciuca
  - admin
  - J. Peraire
  - B. Cockburn

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2017-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2017.09.010'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 350, 951-973

abstract: We devise the first symplectic Hamiltonian hybridizable discontinuous Galerkin (HDG) methods for the acoustic wave equation. We discretize in space by using a Hamiltonian HDG scheme, that is, an HDG method which preserves the Hamiltonian structure of the wave equation, and in time by using symplectic, diagonally implicit and explicit partitioned Runge?Kutta methods. The fundamental feature of the resulting scheme is that the conservation of a discrete energy, which is nothing but a discrete version of the original Hamiltonian, is guaranteed. We present numerical experiments which indicate that the method achieves optimal approximations of order k+1 in the L2-norm when polynomials of degree k?0 and Runge?Kutta time-marching methods of order k+1 are used. In addition, by means of post-processing techniques and by increasing the order of the Runge?Kutta method to k+2, we obtain superconvergent approximations of order k+2 in the L2-norm for the displacement and the velocity. We also present numerical examples that corroborate that the methods conserve energy and that they compare favorably with dissipative HDG schemes, of similar accuracy properties, for long-time simulations.

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
