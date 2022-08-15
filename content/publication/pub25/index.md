---
title: 'A multiscale reduced-basis method for parametrized elliptic partial differential equations with multiple scales'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2008-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2008.07.025'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 227(23), 9807-9822

abstract: We present a technique for solving parametrized elliptic partial differential equations with multiple scales. The technique is based on the combination of the reduced basis method [C. Prud?homme, D. Rovas, K. Veroy, Y. Maday, A.T. Patera, G. Turinici, Reliable real-time solution of parametrized partial differential equations reduced-basis output bound methods, Journal of Fluids Engineering 124 (1) (2002) 70?80] and the multiscale finite element method [T.Y. Hou, X.H. Wu, A multiscale finite element method for elliptic problems in composite materials and porous media, Journal of Computational Physics 134 (1) (1997) 169?189] to treat problems in which the differential coefficient is characterized by a large number of independent parameters. For the multiscale finite element method, a large number of cell problems has to be solved at the fine local mesh for each new configuration of the differential coefficient. In order to improve the computational efficiency of this method, we construct reduced basis spaces that are adapted to the local parameter dependence of the differential operator. The approximate solutions of the cell problems are computed accurately and efficiently via performing Galekin projection onto the reduced basis spaces and implementing the offline?online computational procedure. Therefore, a large number of similar computations at the fine local mesh can be carried out with lower computational cost for each new configuration of the differential coefficient. Numerical results are provided to demonstrate the accuracy and efficiency of the proposed approach.

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
