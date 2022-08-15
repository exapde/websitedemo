---
title: 'Gaussian functional regression for linear partial differential equations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin
  - J. Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2015-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.cma.2015.01.008'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Computer Methods in Applied Mechanics and Engineering
publication_short: Computer Methods in Applied Mechanics and Engineering 287, 69-89

abstract: In this paper, we present a new statistical approach to the problem of incorporating experimental observations into a mathematical model described by linear partial differential equations (PDEs) to improve the prediction of the state of a physical system. We augment the linear PDE with a functional that accounts for the uncertainty in the mathematical model and is modeled as a Gaussian process. This gives rise to a stochastic PDE which is characterized by the Gaussian functional. We develop a Gaussian functional regression method to determine the posterior mean and covariance of the Gaussian functional, thereby solving the stochastic PDE to obtain the posterior distribution for our prediction of the physical state. Our method has the following features which distinguish itself from other regression methods. First, it incorporates both the mathematical model and the observations into the regression procedure. Second, it can handle the observations given in the form of linear functionals of the field variable. Third, the method is non-parametric in the sense that it provides a systematic way to optimally determine the prior covariance operator of the Gaussian functional based on the observations. Fourth, it provides the posterior distribution quantifying the magnitude of uncertainty in our prediction of the physical state. We present numerical results to illustrate these features of the method and compare its performance to that of the standard Gaussian process regression.

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
