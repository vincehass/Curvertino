+++
abstract = "One major challenge in Continual Learning is that the model forgets how to solve earlier tasks commonly known as Catastrophe Forgetting. Extensive work has been recently made in this direction relies of weight regularisation but may not be effective for complex deep neural network. Recently functional regularisation was developed to directly regularise the network output, although computationally expensive, is expected to perform better. However this technique limits the poste- rior expressiveness of fully-factorized Gaussian assumption Cremer et al. (2018) of the inference model. In this work we address this issue without alternating the complexity cost. We propose a Laplace-Gaussian Newton approximation to combine local parametrization and function space learning. This approach finds the mode of the posterior and apply full covariance Gaussian posterior approxi- mation centered on the mode and make the connection to GPs model. By using a Gaussian Process formulation of deep networks, we augment the model to an adaptive variational approximation to account the streaming nature of the data, our approach enables training in weight-space and a regularisation in functional space in a streaming fashion. This formulation enables to resolve common underfitting problem of Laplace approximation. We demonstrate our approach in a Continual Learning setting by combatting Catastrophe Forgetting due to a generalization to non- Gaussian likelihoods. We demonstrate the efficacy of our approach on different classifications problem and provide a meaningful analysis for uncertainty quantification. Finally we identify the benefits of our approach by comparing the performance to the state-of-the-art on standard benchmarks."

authors = ["alison"]
date = "2021-05-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *NIPS Workshop 2021 Under Review*"
publication_short = "NeurIPS"
selected = false
title = "Kronecker-factored approximation (KFAC) of the Laplace-GGN for Continual Learning"
url_code = ""
url_dataset = ""
url_pdf = "pdf/NeurIPS_DNNGP.pdf"
url_project = ""
url_slides = ""
url_video = ""

[[url_custom]]
name = "Proceedings neurips"
url = "https://proceedings.neurips.cc"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
