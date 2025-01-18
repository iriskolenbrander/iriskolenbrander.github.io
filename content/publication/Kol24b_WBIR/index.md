---
title: 'Assessing the Robustness of Image Registration Models Under Domain Shifts with Learnable Input Images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Iris D. Kolenbrander
- Vidya Prasad
- Leanne Zikken
- Maureen A. J. M. van Eijnatten
- Matteo Maspero
- Josien P. W. Pluim

date: '2024-01-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types:
- 'paper-conference'
publication: '*Biomedical Image Registration*'

abstract: Deeep learning models have revolutionized image registration but their accuracy can degrade under unforeseen data variations (domain shifts). It is crucial to assess model robustness under such shifts, often accomplished using simulated domain shifts and expert annotations, e.g., landmarks. This work presents ProactiV-Reg, an annotation-free approach that utilizes a learnable image mapping. It iteratively adjusts a moving image to align with a fixed image under simulated domain shifts. The distances between the perturbed and the optimized images reveal model robustness. We evaluate ProactiV-Reg on three models, showcasing its ability to detect robustness differences, identify dominant perturbations, and provide insights into the model's input requirements.

tags:
- Deep-learning-based image registration
- Robustness
- Learnable input images

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).


