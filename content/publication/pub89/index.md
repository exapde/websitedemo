---
title: 'An HDG method for dissimilar meshes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Manuel Solano
  - Sebastien Terrana
  - admin
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-09-01T00:00:00Z'
doi: '10.1093/imanum/drab059'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IMA Journal of Numerical Analysis
publication_short: IMA Journal of Numerical Analysis 42(2), 1665-1699

abstract: We present a hybridizable discontinuous Galerkin (HDG) method for dissimilar meshes. The method is devised by formulating HDG discretizations on separate meshes and gluing these HDG discretizations through appropriate transmission conditions that weakly enforce the continuity of the numerical trace and the numerical flux across the dissimilar interfaces. The transmission conditions are based upon transferring the numerical flux from the first mesh to the second mesh and the numerical trace from the second mesh to the first one. The transfer of the numerical trace/flux from one mesh to the other relies on the extrapolation of the approximate flux, and is made to be consistent with the HDG methodology for conforming meshes. Stability of the HDG method is shown and the error analysis of the HDG method is established. Numerical results are presented to validate the theoretical results.

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
