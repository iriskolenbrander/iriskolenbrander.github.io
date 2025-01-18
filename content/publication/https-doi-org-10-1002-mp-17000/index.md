---
title: Deep-learning-based joint rigid and deformable contour propagation for magnetic
  resonance imaging-guided prostate radiotherapy
authors:
- Iris D. Kolenbrander
- Matteo Maspero
- Allard A. Hendriksen
- Ryan Pollitt
- Jochem R. N. van der Voort van Zyp
- Cornelis A. T. van den Berg
- Josien P. W. Pluim
- Maureen A. J. M. van Eijnatten
date: '2024-01-01'
publishDate: '2025-01-18T13:01:13.639225Z'
publication_types:
- article-journal
publication: '*Medical Physics*'
doi: https://doi.org/10.1002/mp.17000
abstract: "Abstract Background Deep learning-based unsupervised image registration
  has recently been proposed, promising fast registration. However, it has yet to
  be adopted in the online adaptive magnetic resonance imaging-guided radiotherapy
  (MRgRT) workflow. Purpose In this paper, we design an unsupervised, joint rigid,
  and deformable registration framework for contour propagation in MRgRT of prostate cancer.
  Methods Three-dimensional pelvic T2-weighted MRIs of 143 prostate cancer patients
  undergoing radiotherapy were collected and divided into 110, 13, and 20 patients
  for training, validation, and testing. We designed a framework using convolutional
  neural networks (CNNs) for rigid and deformable registration. We selected the deformable
  registration network architecture among U-Net, MS-D Net, and LapIRN and optimized
  the training strategy (end-to-end vs. sequential). The framework was compared against
  an iterative baseline registration. We evaluated registration accuracy (the Dice
  and Hausdorff distance of the prostate and bladder contours), structural similarity
  index, and folding percentage to compare the methods. We also evaluated the framework's
  robustness to rigid and elastic deformations and bias field perturbations. Results
  The end-to-end trained framework comprising LapIRN for the deformable component
  achieved the best median (interquartile range) prostate and bladder Dice of 0.89
  (0.85–0.91) and 0.86 (0.80–0.91), respectively. This accuracy was comparable to
  the iterative baseline registration: prostate and bladder Dice of 0.91 (0.88–0.93)
  and 0.86 (0.80–0.92). The best models complete rigid and deformable registration
  in 0.002 (0.0005) and 0.74 (0.43) s (Nvidia Tesla V100-PCIe 32 GB GPU), respectively.
  We found that the models are robust to translations up to 52 mm, rotations up to
  15∘$^∘$, elastic deformations up to 40 mm, and bias fields. Conclusions Our proposed
  unsupervised, deep learning-based registration framework can perform rigid and deformable
  registration in less than a second with contour propagation accuracy comparable
  with iterative registration."
tags:
- contour propagation
- deep-learning-based image registration
- MRI-guided radiotherapy
links:
- name: URL
  url: https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.17000
---
