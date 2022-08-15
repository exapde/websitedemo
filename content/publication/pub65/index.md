---
title: 'Gaussian functional regression for output prediction: Model assimilation and experimental design'

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

date: '2016-09-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.jcp.2015.12.035'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Journal of Computational Physics
publication_short: Journal of Computational Physics 309, 52-68

abstract: In this paper, we introduce a Gaussian functional regression (GFR) technique that integrates multi-fidelity models with model reduction to efficiently predict the input?output relationship of a high-fidelity model. The GFR method combines the high-fidelity model with a low-fidelity model to provide an estimate of the output of the high-fidelity model in the form of a posterior distribution that can characterize uncertainty in the prediction. A reduced basis approximation is constructed upon the low-fidelity model and incorporated into the GFR method to yield an inexpensive posterior distribution of the output estimate. As this posterior distribution depends crucially on a set of training inputs at which the high-fidelity models are simulated, we develop a greedy sampling algorithm to select the training inputs. Our approach results in an output prediction model that inherits the fidelity of the high-fidelity model and has the computational complexity of the reduced basis approximation. Numerical results are presented to demonstrate the proposed approach.

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
