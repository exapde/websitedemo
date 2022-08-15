---
title: 'Analysis of HDG methods for Stokes flow'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
  - Bernardo Cockburn 
  - Jayadeep Gopalakrishnan
  - admin  
  - Jaime Peraire
  - Francisco-Javier Sayas

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2011-04-01T00:00:00Z'
doi: 'https://doi.org/10.1090/S0025-5718-2010-02410-X'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Mathematics of Computation
publication_short: Mathematics of Computation 80 (274), 723-760

abstract: In this paper, we analyze a hybridizable discontinuous Galerkin method for numerically solving the Stokes equations. The method uses polynomials of degree k for all the components of the approximate solution of the gradient-velocity-pressure formulation. The novelty of the analysis is the use of a new projection tailored to the very structure of the numerical traces of the method. It renders the analysis of the projection of the errors very concise and allows us to see that the projection of the error in the velocity superconverges. As a consequence, we prove that the approximations of the velocity gradient, the velocity and the pressure converge with the optimal order of convergence of k+1 in L 2 for any k > 0. Moreover, taking advantage of the superconvergence properties of the velocity, we introduce a new element-by-element postprocessing to obtain a new velocity approximation which is exactly divergence-free, H(div)-conforming, and converges with order k+2 for k > 1 and with order 1 for k = 0. Numerical experiments are presented which validate the theoretical results. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
