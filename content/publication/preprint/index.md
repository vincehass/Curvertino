+++
abstract = "One major challenge in Continual Learning is that the model forgets how to solve earlier tasks commonly known as Catastrophic Forgetting. Extensive work has been recently made in this direction relies of weight regularisation but may not be effective for complex deep neural network. Recently functional regularisation was developed to directly regularise the network output, although computationally expensive, is expected to perform better. However this technique limits the posterior expressiveness of fully-factorized Gaussian assumption Cremer et al. (2018) of the inference model. Functional regularisation (Pan et al., 2021) has been developed to combine parameter and function space regularisation but does not take into account structured parameter spaces where have complicated inverse Fisher-matrix computations, which give poor predictives estimates. The method applies a full covariance Gaussian posterior approximation and in case of diagonal posterior approximation it fails to model meaningful relationships. In this work we address this issue without alternating the complexity cost. We propose a Laplace Gauss-Newton approximation to combine local parametrization and function space learning using Kronecker-factored approximation (KFAC) of the Laplace-Gauss-Newton (GGN). We use KFAC (Martens & Grosse, 2020a) posterior approximation for image classification to illustrate how we can model parameter covariances per layer without altering scalability in a Continual Learning setting"





authors = ["Nadhir Hassen"]
date = "2021-05-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *Continual Learning Journal- Under Review*"
publication_short = ""
selected = true
title = "Kronecker-factored approximation (KFAC) of the Laplace-GGN for Continual Learning"
url_code = ""
url_dataset = ""
url_pdf = "pdf/KFAC_paper.pdf"
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = "Continual Learning"
#url = "http://link.springer.com/article/10.1007/s10803-006-0338-0"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
