---
title: 'An explicit hybridizable discontinuous Galerkin method for the acoustic wave equation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - M Stanglmeier
  - admin
  - J Peraire
  - B Cockburn

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2016-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.cma.2015.12.003'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Computer Methods in Applied Mechanics and Engineering 300, 748-769

abstract: We present an explicit hybridizable discontinuous Galerkin (HDG) method for numerically solving the acoustic wave equation. The method is fully explicit, high-order accurate in both space and time, and coincides with the classic discontinuous Galerkin (DG) method with upwinding fluxes for a particular choice of its stabilization function. This means that it has the same computational complexity as other explicit DG methods. However, just as its implicit version, it provides optimal convergence of order for all the approximate variables including the gradient of the solution, and, when the time-stepping method is of order , it displays a superconvergence property which allow us, by means of local postprocessing, to obtain new improved approximations of the scalar field variables at any time levels for which an enhanced accuracy is required. In particular, the new approximations converge with order in the L2 norm for. These properties do not hold for all numerical fluxes. Indeed, our results show that, when the HDG numerical flux is replaced by the Lax?Friedrichs flux, the above-mentioned superconvergence properties are lost, although some are recovered when the Lax?Friedrichs flux is used only in the interior of the domain. Finally, we extend the explicit HDG method to treat the wave equation with perfectly matched layers. We provide numerical examples to demonstrate the performance of the proposed method.

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
