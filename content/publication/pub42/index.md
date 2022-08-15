---
title: 'A posteriori error estimation and basis adaptivity for reduced-basis approximation of nonaffine-parametrized linear elliptic partial differential equations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2007-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2007.08.031'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 227(2), 983-1006

abstract: In this paper, we extend the earlier work [M. Barrault, Y. Maday, N. C. Nguyen, A.T. Patera, An ?empirical interpolation? method application to efficient reduced-basis discretization of partial differential equations, C.R. Acad. Sci. Paris, Serie I 339 (2004) 667?672; M.A. Grepl, Y. Maday, N.C. Nguyen, A.T. Patera, Efficient reduced-basis treatment of nonaffine and nonlinear partial differential equations, M2AN Math. Model. Numer. Anal. 41 (3) (2007) 575?605.] to provide a posteriori error estimation and basis adaptivity for reduced-basis approximation of linear elliptic partial differential equations with nonaffine parameter dependence. The essential components are (i) rapidly convergent reduced-basis approximations ? (Galerkin) projection onto a space spanned by N global hierarchical basis functions which are constructed from solutions of the governing partial differential equation at judiciously selected points in parameter space; (ii) stable and inexpensive interpolation procedures ? methods which allow us to replace nonaffine parameter functions with a coefficient-function expansion as a sum of M products of parameter-dependent coefficients and parameter-independent functions; (iii) a posteriori error estimation ? relaxations of the error-residual equation that provide inexpensive yet sharp error bounds for the error in the outputs of interest; (iv) optimal basis construction ? processes which make use of the error bounds as an inexpensive surrogate for the expensive true error to explore the parameter space in the quest for an optimal sampling set; and (v) offline/online computational procedures ? methods which decouple the generation and projection stages of the approximation process. The operation count for the online stage - in which, given a new parameter value, we calculate the output of interest and associated error bounds - depends only on N, M, and the affine parametric complexity of the problem; the method is thus ideally suited for repeated and reliable evaluation of input?output relationships in the many-query or real-time contexts.

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
