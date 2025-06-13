---
title: "Unsupervised representation learning of Kohn–Sham states and consequences for downstream predictions of many-body effects"
authors:
- Bowen Hou
- admin
- Diana Y. Qiu
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-11-02"
doi: "https://doi.org/10.1038/s41467-024-53748-7"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Nature Communication"
publication_short: ""

abstract: Representation learning for the electronic structure problem is a major challenge of machine learning in computational condensed matter and materials physics. Within quantum mechanical first principles approaches, density functional theory (DFT) is the preeminent tool for understanding electronic structure, and the high-dimensional DFT wavefunctions serve as building blocks for downstream calculations of correlated many-body excitations and related physical observables. Here, we use variational autoencoders (VAE) for the unsupervised learning of DFT wavefunctions and show that these wavefunctions lie in a low-dimensional manifold within latent space. Our model autonomously determines the optimal representation of the electronic structure, avoiding limitations due to manual feature engineering. To demonstrate the utility of the latent space representation of the DFT wavefunction, we use it for the supervised training of neural networks (NN) for downstream prediction of quasiparticle bandstructures within the GW formalism. The GW prediction achieves a low error of 0.11 eV for a combined test set of two-dimensional metals and semiconductors, suggesting that the latent space representation captures key physical information from the original data. Finally, we explore the generative ability and interpretability of the VAE representation.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- GW-BSE
- Unsupervised machine learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.nature.com/articles/s41467-024-53748-7.pdf
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-->
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
-->