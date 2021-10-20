## Predicting Solar Flares with Ensemble Machine Learning<br>
[![DOI](https://zenodo.org/badge/417927505.svg)](https://zenodo.org/badge/latestdoi/417927505)

## Authors
Yasser Abduallah, Jason T. L. Wang, Haimin Wang

## Abstract
<p>Solar flare prediction plays an important role in understanding and forecasting space weather. The main goal of the Helioseismic and Magnetic Imager (HMI), one of the instruments on NASA's Solar Dynamics Observatory, is to study the origin of solar variability and characterize the Sun's magnetic activity. HMI provides continuous full-disk observations of the solar vector magnetic field with high cadence data that lead to reliable predictive capability; yet, solar flare prediction effort utilizing these data is still limited. In this paper, we present a machine-learning-as-a-service (MLaaS) framework, called DeepSun, for predicting solar flares on the Web based on HMI's data products. Specifically, we construct training data by utilizing the physical parameters provided by the Space-weather HMI Active Region Patches (SHARP) and categorize solar flares into four classes, namely B, C, M, X, according to the X-ray flare catalogs available at the National Centers for Environmental Information (NCEI). Thus, the solar flare prediction problem at hand is essentially a multi-class (i.e., four-class) classification problem. The DeepSun system employs several machine learning algorithms to tackle this multi-class prediction problem and provides an application programming interface (API) for remote programming users.</p>

## Binder

This notebook is Binder enabled and can be run on [mybinder.org](https://mybinder.org/) by using the link below.


### ccsc_FlareML.ipynb (Jupyter Notebook for FlareML)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ccsc-tools/FlareML/HEAD?labpath=ccsc_FlareML.ipynb)

Please note that starting Binder might take some time to create and start the image.


## Installation on local machine

|Library | Version   | Description  |
|---|---|---|
|numpy| 1.19.5| Array manipulation|
|scikit-learn| 0.24.2| Machine learning|
| sklearn-extensions | 0.0.2  | Extension for scikit-learn |
| pandas|1.2.4| Data loading and manipulation|
