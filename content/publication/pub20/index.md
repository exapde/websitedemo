---
title: 'A comparison of HDG methods for Stokes flow'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Bernardo Cockburn
  - admin
  - Jaume Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2010-09-01T00:00:00Z'
doi: 'https://doi.org/10.1007/s10915-010-9359-0'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Scientific Computing
publication_short: Journal of Scientific Computing 45(1), 215-237

abstract: In this paper, we compare hybridizable discontinuous Galerkin (HDG) methods for numerically solving the velocity-pressure-gradient, velocity-pressure-stress, and velocity-pressure-vorticity formulations of Stokes flow. Although they are defined by using different formulations of the Stokes equations, the methods share several common features. First, they use polynomials of degree k for all the components of the approximate solution. Second, they have the same globally coupled variables, namely, the approximate trace of the velocity on the faces and the mean of the pressure on the elements. Third, they give rise to a matrix system of the same size, sparsity structure and similar condition number. As a result, they have the same computational complexity and storage requirement. And fourth, they can provide, by means of an element-by element postprocessing, a new approximation of the velocity which, unlike the original velocity, is divergence-free and H(div)-conforming. We present numerical results showing that each of the approximations provided by these three methods converge with the optimal order of k+1 in L 2 for any k?0. We also display experiments indicating that the postprocessed velocity is a better approximation than the original approximate velocity. It converges with an additional order than the original velocity for the gradient-based HDG, and with the same order for the vorticity-based HDG methods. For the stress-based HDG methods, it seems to converge with an additional order for even polynomial degree approximations. Finally, the numerical results indicate that the method based on the velocity-pressure-gradient formulation provides the best approximations for similar computational complexity.

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
