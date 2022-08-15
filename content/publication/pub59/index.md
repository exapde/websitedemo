---
title: 'Hybridized discontinuous Galerkin methods for wave propagation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - P. Fernandez
  - A. Christophe
  - S. Terrana
  - admin
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2018-09-01T00:00:00Z'
doi: '10.1007/s10915-018-0811-x'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Scientific Computing
publication_short: Journal of Scientific Computing 77(3), 1566-1604

abstract: We present the recent development of hybridizable and embedded discontinuous Galerkin (DG) methods for wave propagation problems in fluids, solids, and electromagnetism. In each of these areas, we describe the methods, discuss their main features, display numerical results to illustrate their performance, and conclude with bibliography notes. The main ingredients in devising these DG methods are (1) a local Galerkin projection of the underlying partial differential equations at the element level onto spaces of polynomials of degree k to parametrize the numerical solution in terms of the numerical trace; (2) a judicious choice of the numerical flux to provide stability and consistency; and (3) a global jump condition that enforces the continuity of the numerical flux to obtain a global system in terms of the numerical trace. These DG methods are termed hybridized DG methods, because they are amenable to hybridization (static condensation) and hence to more efficient implementations. They share many common advantages of DG methods and possess some unique features that make them well-suited to wave propagation problems.

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
