# 3rd Place Solution in 2022 Enerjisa Datathon

Here is my solution:

1. I have read a lot of papers (articles, thesis etc.) because the most importance features (from my perspective) come from domain-specific informations.

2. I mostly focus on external data like sun position, irradiance etc. You can use this library: https://pvlib-python.readthedocs.io/en/stable/index.html

3. Another extraordinary thing was Campbell-Norman (1988) method. I calculated irradiance using Effective Cloud Cover and GHI-DHI-DNI, you can see the method here: https://pvlib-python.readthedocs.io/en/stable/forecasts.html?highlight=campbell#cloud-cover-and-radiation

4. My feature selection method (LOFO) is coming from: https://github.com/aerdem4/lofo-importance

Some of my references (the tip of the iceberg): 

William F. Holmgren, Clifford W. Hansen, and Mark A. Mikofski. “pvlib python: a python package for modeling solar energy systems.” Journal of Open Source Software, 3(29), 884, (2018). https://doi.org/10.21105/joss.00884

Campbell, G. S., J. M. Norman (1998) An Introduction to Environmental Biophysics. 2nd Ed. New York: Springer.

Wang Y, Feng B, Hua Q-S, Sun L. Short-Term Solar Power Forecasting: A Combined Long Short-Term Memory and Gaussian Process Regression Method. Sustainability. 2021; 13(7):3665. https://doi.org/10.3390/su13073665

Ertekin, S. (2020). Solar Power Prediction with an Hour-based Ensemble Machine Learning Method . Hittite Journal of Science and Engineering , 7 (1) , 35-40 . DOI: 10.17350/HJSE19030000169

Daniel O, Kubby J. Feature Selection and ANN Solar Power Prediction. Research Article. Journal of Renewable Energy, 2017. https://doi.org/10.1155/2017/2437387
