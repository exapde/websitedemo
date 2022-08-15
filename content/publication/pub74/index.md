---
title: 'Computing parametrized solutions for plasmonic nanogap structures'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - F. Vidal-Codina
  - admin
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2018-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2018.04.009'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 366, 89-106

abstract: The interaction of electromagnetic waves with metallic nanostructures generates resonant oscillations of the conduction-band electrons at the metal surface. These resonances can lead to large enhancements of the incident field and to the confinement of light to small regions, typically several orders of magnitude smaller than the incident wavelength. The accurate prediction of these resonances entails several challenges. Small geometric variations in the plasmonic structure may lead to large variations in the electromagnetic field responses. Furthermore, the material parameters that characterize the optical behavior of metals at the nanoscale need to be determined experimentally and are consequently subject to measurement errors. It then becomes essential that any predictive tool for the simulation and design of plasmonic structures accounts for fabrication tolerances and measurement uncertainties. In this paper, we develop a reduced order modeling framework that is capable of real-time accurate electromagnetic responses of plasmonic nanogap structures for a wide range of geometry and material parameters. The main ingredients of the proposed method are (i) the hybridizable discontinuous Galerkin method to numerically solve the equations governing electromagnetic wave propagation in dielectric and metallic media, (ii) a reference domain formulation of the time-harmonic Maxwell's equations to account for arbitrary geometry variations; and (iii) proper orthogonal decomposition and empirical interpolation techniques to construct an efficient reduced model. To demonstrate effectiveness of the models developed, we analyze geometry sensitivities and explore optimal designs of a 3D periodic coaxial nanogap structure.

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
