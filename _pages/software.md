---
permalink: /software/
title: "Software"
classes: smaller_font
author_profile: true
header:
  overlay_image: /assets/images/seattle-night.jpg
  caption: "Photo credit: [**Timothy Eberly on Unsplash**](https://unsplash.com/photos/h3vT1-T2nfc)"
  actions:
    - label: "Github"
      url: "https://github.com/elayden/"
---
----------------------------------------------------------------------------	
### [N-Back Memory Training](https://nbackmemorytraining.com/)			 	         	       	 	
* Java-based Android app on [Google Play](https://play.google.com/store/apps/details?id=science.eal.n_backmemorytraining) for n-back working memory training
* 4.6 star rating, 10k+ monthly active users, 25k+ lines of Java
* Scoring with discrimination index (A’) from signal detection theory
* Data management using Firebase Realtime Database and SQLite
	
----------------------------------------------------------------------------	
### [NIfTI Studio](https://elliotlayden.com/software/nifti-studio)
* Open-source toolbox for NIfTI and Analyze (img/hdr) image visualization, editing, and 3D rendering
* View on [Github](https://github.com/elayden/NIfTI-Studio), [Citation](http://doi.org/10.5281/zenodo.3725006)

----------------------------------------------------------------------------		
### [MRIqual](https://elliotlayden.com/software/mriqual)
* Open-source toolbox toolbox for quality assurance analyses on structural and functional MRI images
* View on [Github](https://github.com/elayden/MRIqual), [Citation](http://doi.org/10.5281/zenodo.3735471)
	
----------------------------------------------------------------------------
### [Portfolio Sortino Ratio](https://elliotlayden.com/software/portfolio_sortino_ratio)
* Optimize stock portfolio weights to maximize a combination of Sortino ratio, Sharpe ratio, total return, downside risk, SD, or max drawdown
* View on [Github](https://github.com/elayden/portfolio_sortino_ratio), [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/68589-portfolio_sortino_ratio)
	
----------------------------------------------------------------------------
### N-Back for Matlab
* The classic dual n-back task implemented in Matlab; includes position, sound, and color 
* View on [Github](https://github.com/elayden/N-Back-for-Matlab), [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/67976-n-back-for-matlab), [G-Node Open Data](https://doi.org/10.12751/g-node.f87128)

----------------------------------------------------------------------------
### Plot Corrmat
* A Matlab utility for plotting correlation matrices, with similar appearance to Seaborn in Python.
* View on [Github](https://github.com/elayden/plot-corrmat), [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/73845-plot-corrmat)
	
----------------------------------------------------------------------------
### Simple Cohen's Kappa
* A simple and easy-to-use implementation of the inter-rater reliability measure Cohen's kappa (κ)
* Cohen's kappa is normalized for the percent agreement expected by chance due to class imbalance
* View on [Github](https://github.com/elayden/cohensKappa), [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/69943-simple-cohen-s-kappa)

----------------------------------------------------------------------------
### fast_corr
* Rapidly calculates column-wise Pearson correlations between large matrices using a vectorized method
* An order of magnitude faster than Matlab built-in corr.m to compute the full correlation matrix
* View on [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/63082-fast_corr)

----------------------------------------------------------------------------
### Intrinsic Connectivity Contrast (ICC)
* A simple utility for efficiently computing the ICC, a measure of degree centrality for weighted networks
* This function was inspired by Martuzzi et al. (2011) and used in some of my neuroimaging research (Layden et al., 2017)
* View on [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/68248-intrinsic_connectivity_contrast)
	
<p style="text-align: center;"><b>References</b></p>
Layden, E. A., Cacioppo, J. T., Cacioppo, S., Cappa, S. F., Dodich, A., Falini, A., & Canessa, N. (2017). Perceived social isolation is associated with altered functional connectivity in neural networks associated with tonic alertness and executive control. <i>Neuroimage</i>, <i>145</i>, 58-73.

Martuzzi, R., Ramani, R., Qiu, M., Shen, X., Papademetris, X., & Constable, R. T. (2011). A whole-brain voxel based measure of intrinsic connectivity contrast reveals local changes in tissue connectivity with anesthetic without a priori assumptions on thresholds or regions of interest. <i>Neuroimage</i>, <i>58</i>(4), 1044-1050.

----------------------------------------------------------------------------