# CovaPT
Analytic covariance of the galaxy power spectrum multipoles based on [arXiv:1910.02914](https://arxiv.org/abs/1910.02914)


The modules currently uploaded are for:

1) Covariance for a periodic box in real space (Periodic_Box.ipynb)

2) Gaussian covariance for an arbitrary survey window (Covariance_SurveyGeometry.ipynb)

3) Calculating window kernels for Gaussian covariance (Survey_window_kernels.ipynb)
   - The corresponding formulae are in CovaPT_Formulae.pdf


The modules left to upload are (apologies for the delay):

4) non-Gaussian covariance (with and without survey geometry),
   which includes the regular trispectrum and super sample covariance
   
5) Calculating cartesian FFTs from the survey random catalog, which are needed for Covariance_SurveyGeometry.ipynb

6) Code for calculating the Fisher forecast in Fig.1 of [arXiv:2009.00622](https://arxiv.org/abs/2009.00622) which uses the[CLASS-PT code](https://github.com/Michalychforever/CLASS-PT). Also, a code showing how CovaPT can be used with CLASS-PT.


If you are interested in more details about a particular part of the calculation, please feel free to email me at: jay.wadekar@nyu.edu
I would love to hear feedback about the accesibility of the code and if adding any other module for the redshift space covariance would be interesting.

The input data files used in the code can be downloaded from
[here](https://drive.google.com/drive/folders/1bWKfUaIXcC1n-2hk9KtKhqukxTH1379i?usp=sharing)

Authors: Digvijay (Jay) Wadekar and Roman Scoccimarro
