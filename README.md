# CovaPT
Analytic covariance of the galaxy power spectrum multipoles based on [arXiv:1910.02914](https://arxiv.org/abs/1910.02914)

Authors: Jay Wadekar and Roman Scoccimarro

with contributions from Otavio Alves.

The modules currently uploaded are for:

1. Covariance for a box (Covariance_BoxGeometry.ipynb)

2. Covariance for an arbitrary survey window (Covariance_SurveyGeometry.ipynb)

3. Calculating window kernels for Gaussian covariance (Survey_window_kernels.ipynb)
   - The corresponding formulae are in CovaPT_Formulae.pdf
   
4. Calculating cartesian FFTs from the survey random catalog (./detail/Survey_Window_FFTs.ipynb)
    - which are needed for Survey_window_kernels.ipynb

For ease in viewing different modules in these notebooks, please install [jupyter_contrib_nbextensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html) and activate [collapsible headings](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/collapsible_headings/readme.html)

The following remaining modules will be uploaded soon (apologies for the delay):
  
* Hexadecapole calculations in addition to Monopole+Quadrupole

* Code for calculating the Fisher forecast in Fig.1 of [arXiv:2009.00622](https://arxiv.org/abs/2009.00622)
    - This uses the [CLASS-PT code](https://github.com/Michalychforever/CLASS-PT). I'll also upload a notebook showing how CovaPT can be used with CLASS-PT.

If you are interested in more details about a particular part of the calculation, please feel free to email me at: jayw@ias.edu

I would love to hear feedback about the accesibility of the code and if adding any more modules for the power spectrum covariance would be useful. I also thank Albert Chuang, Yan Lai for helpful comments related to the code.

The input data files used in the code can be downloaded from
[here](https://drive.google.com/drive/folders/1bWKfUaIXcC1n-2hk9KtKhqukxTH1379i?usp=sharing)

Extra codes/files:

Covariance for matter power spectrum (Gaussian+tree-level trispectrum) instead of galaxies is in Extras/Matter_covariance.ipynb


