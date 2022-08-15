---
title: '?Natural norm? a posteriori error estimators for reduced basis approximations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Sugata Sen
  - Karen Veroy
  - Dinh Bao Phuong Huynh
  - Simone Deparis
  - admin
  - Anthony T Patera

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2006-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2006.02.012'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 217(1), 37-62

abstract: We present a technique for the rapid and reliable prediction of linear-functional outputs of coercive and non-coercive linear elliptic partial differential equations with affine parameter dependence. The essential components are (i) rapidly convergent global reduced basis approximations ? (Galerkin) projection onto a space WN spanned by solutions of the governing partial differential equation at N judiciously selected points in parameter space; (ii) a posteriori error estimation ? relaxations of the error-residual equation that provide inexpensive yet sharp bounds for the error in the outputs of interest; and (iii) offline/online computational procedures ? methods which decouple the generation and projection stages of the approximation process. The operation count for the online stage ? in which, given a new parameter value, we calculate the output of interest and associated error bound ? depends only on N (typically very small) and the parametric complexity of the problem. In this paper we propose a new ?natural norm? formulation for our reduced basis error estimation framework that (a) greatly simplifies and improves our inf?sup lower bound construction (offline) and evaluation (online) ? a critical ingredient of our a posteriori error estimators; and (b) much better controls ? significantly sharpens ? our output error bounds, in particular (through deflation) for parameter values corresponding to nearly singular solution behavior. We apply the method to two illustrative problems a coercive Laplacian heat conduction problem ? which becomes singular as the heat transfer coefficient tends to zero; and a non-coercive Helmholtz acoustics problem ? which becomes singular as we approach resonance. In both cases, we observe very economical and sharp construction of the requisite natural-norm inf?sup lower bound; rapid convergence of the reduced basis approximation; reasonable effectivities (even for near-singular behavior) for our deflated output error estimators; and significant ? several order of magnitude ? (online) computational savings relative to standard finite element procedures.

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
