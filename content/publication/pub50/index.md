---
title: 'A hybridizable discontinuous Galerkin method for computing nonlocal electromagnetic effects in three-dimensional metallic nanostructures'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - F. Vidal-Codina
  - admin
  - S. H. Oh
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2018-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2017.11.025'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 355, 548-565

abstract: The interaction of light with metallic nanostructures produces a collective excitation of electrons at the metal surface, also known as surface plasmons. These collective excitations lead to resonances that enable the confinement of light in deep-subwavelength regions, thereby leading to large near-field enhancements. The simulation of plasmon resonances presents notable challenges. From the modeling perspective, the realistic behavior of conduction-band electrons in metallic nanostructures is not captured by Maxwell's equations, thus requiring additional modeling. From the simulation perspective, the disparity in length scales stemming from the extreme field localization demands efficient and accurate numerical methods. In this paper, we develop the hybridizable discontinuous Galerkin (HDG) method to solve Maxwell's equations augmented with the hydrodynamic model for the conduction-band electrons in noble metals. This method enables the efficient simulation of plasmonic nanostructures while accounting for the nonlocal interactions between electrons and the incident light. We introduce a novel postprocessing scheme to recover superconvergent solutions and demonstrate the convergence of the proposed HDG method for the simulation of a 2D gold nanowire and a 3D periodic annular nanogap structure. The results of the hydrodynamic model are compared to those of a simplified local response model, showing that differences between them can be significant at the nanoscale.

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
