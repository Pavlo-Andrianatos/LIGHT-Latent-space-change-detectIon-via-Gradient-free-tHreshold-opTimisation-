# Improving Change Detection with Gradient-Free Optimisation and Semi-Supervised Learning
----

[![License: CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

>**Abstract:** Satellite image change detection is the task of identifying meaningful differences between temporal satellite images. In recent years, convolutional neural networks (CNNs), especially architectures like U-Net, have been widely adopted due to their effectiveness in extracting semantic image features. This study proposes a semi-supervised change detector operating in a U-Net encoder’s latent feature space, titled LIGHT, where pairwise feature differences are compared against learned thresholds. Automatic optimisation of thresholds is achieved in a semi-supervised manner via gradient-free methods, requiring as few as 10 to 15 labelled change images. The methods tested in this study include covariance matrix adaptation evolution strategy (CMA-ES), particle swarm optimisation (PSO), genetic algorithms (GA), and Markov chain Monte Carlo (MCMC). Experiments across the Vaihingen, HRSCD, and SyntheWorld datasets show that optimisation performance is dataset-dependent, with PSO emerging as the most effective optimiser. While the proposed approach does not match fully supervised state-of-the-art methods in change detection accuracy, it achieves a competitive score with substantially fewer annotations. Examination of raw tensor outputs shows the underlying difference mechanism's sensitivity to true change areas pointing towards richer future extensions that could further close the performance gap. Source code is available at https://github.com/Pavlo-Andrianatos/LIGHT-Latent-space-change-detectIon-via-Gradient-free-tHreshold-opTimisation.

----

## Requirements
Set up and activate the virtual [conda](https://docs.anaconda.com/anaconda/install/index.html) environment: 
- `conda env create -f environment.yml`
- `conda activate LIGHTChangeDetectionFramework`
----

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
