---
title: 'GPU-accelerated Large Eddy Simulation of Hypersonic Flows'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Sebastien Terrana
  - admin
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-09-01T00:00:00Z'
doi: '10.2514/6.2020-1062'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: AIAA Scitech 2020 Forum
publication_short: AIAA Scitech 2020 Forum, 1062

abstract:  High-order discontinuous Galerkin (DG) methods have emerged as an attractive approach for large eddy simulation of turbulent flows owing to their high accuracy and implicit dissipation properties. However, the application of DG methods for hypersonic flows is still challenging due to the high-computational cost and the lack of robust shock capturing algorithms. In this paper, we adreess the efficiency and robustness of Discontinuous Galerkin methods. To that end we develop a high-order implicit discontinuous Galerkin method for the numerical simulation of hypersonic flows on graphics processors (GPUs). The main ingredients in our approach include i) implicit high-order DG approximation on unstructured/adapted meshes, ii) shock capturing for hypersonic flows, iii) iterative solution methods with CUDA/MPI implementation on GPU clusters, and iv) effective matrix-free preconditioner with reduced basis approximation of the Jacobian matrix. Numerical results on several test cases are presented to validate our method. 

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
