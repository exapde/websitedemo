---
title: 'Symplectic Hamiltonian finite element methods for electromagnetics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Manuel A. Sanchez
  - Shukai Du
  - Bernardo Cockburn
  - admin
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-01-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.cma.2022.114969'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Computer Methods in Applied Mechanics and Engineering 396, 114969

abstract: We present several high-order accurate finite element methods for the Maxwell?s equations which provide time-invariant, non-drifting approximations to the total electric and magnetic charges, and to the total energy. We devise these methods by taking advantage of the Hamiltonian structures of the Maxwell?s equations as follows. First, we introduce spatial discretizations of the Maxwell?s equations using mixed finite element, discontinuous Galerkin, and hybridizable discontinuous Galerkin methods to obtain a semi-discrete system of equations which display discrete versions of the Hamiltonian structure of the Maxwell?s equations. Then we discretize the resulting semi-discrete system in time by using a symplectic integrator. This ensures the conservation properties of the fully discrete system of equations. For the Symplectic Hamiltonian HDG method, we present numerical experiments which confirm its optimal orders of convergence for all variables and its conservation properties for the total linear and angular momenta, as well as the total energy. Finally, we discuss the extension of our results to other boundary conditions and to numerical schemes defined by different weak formulations.

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
