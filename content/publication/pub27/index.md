---
title: 'Navier-Stokes solution using hybridizable discontinuous Galerkin methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - David Moro
  - admin
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2011-09-01T00:00:00Z'
doi: 'https://doi.org/10.2514/6.2011-3407'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 20th AIAA computational fluid dynamics conference
publication_short: 20th AIAA computational fluid dynamics conference, 3407

abstract: We are concerned with the numerical solution of the Navier-Stokes and Reynolds-averaged Navier-Stokes equations using hybridizable discontinuous Galerkin (HDG) meth- ods recently introduced in Ref. [36]. These methods are computationally more efficient and accurate than other discontinuous Galerkin methods. They are thus well-suited for solving many CFD problems. However, the HDG methods can not directly deal with viscous com- pressible flows with shock waves. We thus propose to add an artificial viscosity term to the Navier-Stokes equations. Moreover, in order to render the Spalart-Allmaras (SA) tur- bulence model easier to integrate using HDG methods, we propose a simple modification of the SA model. The modification is effective only in regions where the eddy viscosity is smaller than the molecular viscosity. Therefore, it does not affect the numerical prediction of flow quantities as compared to the original SA model. Numerical results are presented to demonstrate the proposed approach.

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
