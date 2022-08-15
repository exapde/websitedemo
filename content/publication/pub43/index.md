---
title: 'A hybridized discontinuous Petrov-Galerkin scheme for scalar conservation laws'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - D. Moro
  - admin
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2012-09-01T00:00:00Z'
doi: 'https://doi.org/10.1002/nme.4300'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: International Journal for Numerical Methods in Engineering
publication_short: International Journal for Numerical Methods in Engineering 91(9), 950-970

abstract: We present a hybridized discontinuous Petrov?Galerkin (HDPG) method for the numerical solution of steady and time-dependent scalar conservation laws. The method combines a hybridization technique with a local Petrov?Galerkin approach in which the test functions are computed to maximize the inf-sup condition. Since the Petrov?Galerkin approach does not guarantee a conservative solution, we propose to enforce this explicitly by introducing a constraint into the local Petrov?Galerkin problem. When the resulting nonlinear system is solved using the Newton?Raphson procedure, the solution inside each element can be locally condensed to yield a global linear system involving only the degrees of freedom of the numerical trace. This results in a significant reduction in memory storage and computation time for the solution of the matrix system, albeit at the cost of solving the local Petrov?Galerkin problems. However, these local problems are independent of each other and thus perfectly scalable. We present several numerical examples to assess the performance of the proposed method. The results show that the HDPG method outperforms the hybridizable discontinuous Galerkin method for problems involving discontinuities. Moreover, for the test case proposed by Peterson, the HDPG method provides optimal convergence of order k?+?1.

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
