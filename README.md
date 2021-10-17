# CovaPT
Analytic covariance of the galaxy power spectrum multipoles based on [arXiv:1910.02914](https://arxiv.org/abs/1910.02914)

The modules currently uploaded are for:

1. Covariance for a box (Covariance_BoxGeometry.ipynb)

2. Covariance for an arbitrary survey window (Covariance_SurveyGeometry.ipynb)

3. Calculating window kernels for Gaussian covariance (Survey_window_kernels.ipynb)
   - The corresponding formulae are in CovaPT_Formulae.pdf

For ease in viewing different modules in these notebooks, please install [jupyter_contrib_nbextensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html) and activate [collapsible headings](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/collapsible_headings/readme.html)

The following remaining modules will be uploaded soon (apologies for the delay):
  
* Hexadecapole calculations in addition to Monopole+Quadrupole
 
* Calculating cartesian FFTs from the survey random catalog
    - which are needed for Covariance_SurveyGeometry.ipynb

* Code for calculating the Fisher forecast in Fig.1 of [arXiv:2009.00622](https://arxiv.org/abs/2009.00622)
    - This uses the [CLASS-PT code](https://github.com/Michalychforever/CLASS-PT). I'll also upload a notebook showing how CovaPT can be used with CLASS-PT.

If you are interested in more details about a particular part of the calculation, please feel free to email me at: jayw@ias.edu

I would love to hear feedback about the accesibility of the code and if adding any more modules for the power spectrum covariance would be useful.

Authors: Digvijay (Jay) Wadekar and Roman Scoccimarro

The input data files used in the code can be downloaded from
[here](https://drive.google.com/drive/folders/1bWKfUaIXcC1n-2hk9KtKhqukxTH1379i?usp=sharing)
