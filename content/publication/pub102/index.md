---
title: 'A posteriori goal-oriented bounds for the Poisson problem using potential and equilibrated flux reconstructions: Application to the hybridizable discontinuous Galerkin method'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - N. Pares
  - admin
  - P. Diez
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-01-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.cma.2021.114088'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Computer Methods in Applied Mechanics and Engineering 386, 114088

abstract: We present a general framework to compute upper and lower bounds for linear-functional outputs of the exact solutions of the Poisson equation based on reconstructions of the field variable and flux for both the primal and adjoint problems. The method is devised from a generalization of the complementary energy principle and the duality theory. Using duality theory, the computation of bounds is reduced to finding independent potential and equilibrated flux reconstructions. A generalization of this result is also introduced allowing to derive alternative guaranteed bounds from nearly-arbitrary H(div;?) flux reconstructions (only zero-order equilibration is required). This approach is applicable to any numerical method used to compute the solution. In this work, the proposed approach is applied to derive bounds for the hybridizable discontinuous Galerkin (HDG) method. An attractive feature of the proposed approach is that superconvergence on the bound gap is achieved, yielding accurate bounds even for very coarse meshes. Numerical experiments are presented to illustrate the performance and convergence of the bounds for the HDG method in both uniform and adaptive mesh refinements.

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
