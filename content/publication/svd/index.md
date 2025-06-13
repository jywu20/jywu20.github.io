---
title: 'Data-driven Low-rank Approximation for Electron-hole Kernel and Acceleration of Time-dependent GW Calculations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bowen Hou
  - admin
  - Victor Chang Lee
  - Jiaxuan Guo
  - Luna Y. Liu
  - Diana Y. Qiu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-08'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: Many-body electron-hole interactions are essential for understanding non-linear optical processes and ultrafast spectroscopy of materials. Recent first principles approaches based on nonequilibrium Green's function formalisms, such as the time-dependent adiabatic GW (TD-aGW) approach, can predict the nonequilibrium dynamics of excited states including electron-hole interactions. However, the high dimensionality of the electron-hole kernel poses significant computational challenges for scalability. Here, we develop a data-driven low-rank approximation for the electron-hole kernel, leveraging localized excitonic effects in the Hilbert space of crystalline systems. Through singular value decomposition (SVD) analysis, we show that the subspace of non-zero singular values, containing the key information of the electron-hole kernel, retains a small size even as the k-grid grows, ensuring computational feasibility with extremely dense k-grids for converged calculations. Utilizing this low-rank property, we achieve at least 95% compression of the kernel and an order-of-magnitude speedup of TD-aGW calculations. Our method, rooted in physical interpretability, outperforms existing machine learning approaches by avoiding intensive training processes and eliminating time-accumulated errors, providing a general framework for high-throughput, nonequilibrium simulation of light-driven dynamics in materials.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Unsupervised learning
  - SVD
  - Non-equilibrium Dynamics
  - GW-BSE

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2502.05635'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

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
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
