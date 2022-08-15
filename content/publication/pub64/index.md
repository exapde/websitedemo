---
title: 'A hybridizable discontinuous Galerkin method for both thin and 3D nonlinear elastic structures'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - S. Terrana
  - admin
  - J. Bonet
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2019-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.cma.2019.04.029'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Computer Methods in Applied Mechanics and Engineering 352, 561-585

abstract: We present a 3D hybridizable discontinuous Galerkin (HDG) method for nonlinear elasticity which can be efficiently used for thin structures with large deformation. The HDG method is developed for a three-field formulation of nonlinear elasticity and is endowed with a number of attractive features that make it ideally suited for thin structures. Regarding robustness, the method avoids a variety of locking phenomena such as membrane locking, shear locking, and volumetric locking. Regarding accuracy, the method yields optimal convergence for the displacements, which can be further improved by an inexpensive postprocessing. And finally, regarding efficiency, the only globally coupled unknowns are the degrees of freedom of the numerical trace on the interior faces, resulting in substantial savings in computational time and memory storage. This last feature is particularly advantageous for thin structures because the number of interior faces is typically small. In addition, we discuss the implementation of the HDG method with arc-length algorithms for phenomena such as snap-through, where the standard load incrementation algorithm becomes unstable. Numerical results are presented to verify the convergence and demonstrate the performance of the HDG method through simple analytical and popular benchmark problems in the literature.

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
