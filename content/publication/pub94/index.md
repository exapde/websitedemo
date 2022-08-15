---
title: 'Large-Eddy Simulation of Transonic Buffet Using Matrix-Free Discontinuous Galerkin Method'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - admin
  - Sebastien Terrana
  - Jaime Peraire

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-01-01T00:00:00Z'
doi: '10.2514/1.J060459'

# Schedule page publish date (NOT publication's date).
# publishDate: '2009-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: AIAA Journal
publication_short: AIAA Journal 60(5), 3060-3077

abstract: We present an implicit large-eddy simulation of transonic buffet over the OAT15A supercritical airfoil at Mach number 0.73, angle of attack 3.5 degrees, and Reynolds number 3 millions. The simulation is performed using a matrix-free discontinuous Galerkin (DG) method and a diagonally implicit Runge-Kutta scheme on graphics processor units. We propose a Jacobian-free Newton-Krylov method to solve nonlinear systems arising from the discretization of the Navier?Stokes equations. The method successfully predicts the buffet onset, the buffet frequency, and turbulence statistics owing to the high-order DG discretization and an efficient mesh refinement for the laminar and turbulent boundary layers. A number of physical phenomena present in the experiment are captured in our simulation, including periodical low-frequency oscillations of shock wave in the streamwise direction, strong shear layer detached from the shock wave due to shock-wave/boundary-layer interaction and small-scale structures broken down by the shear-layer instability in the transition region, and shock-induced flow separation. The pressure coefficient, the root mean square of the fluctuating pressure, and the streamwise range of the shock wave oscillation agree well with the experimental data. The results suggest that the proposed method can accurately predict the onset of turbulence and buffet phenomena at high Reynolds numbers without a subgrid scale model or a wall model. 

tags: 'FearuredResearch'

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
