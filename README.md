Notebooks created in Google Colab.

These notebooks serve as exercises in implementing neural networks in PyTorch and in preprocessing time series data for use with these neural networks. The goal here is to practice implementation and data preprocessing rather than to achieve any "state-of-the-art" results, hence, extensive diagnostics of the models are not given in much depth here. 
* Dataset used can be downloaded from: https://data.nasa.gov/Aerospace/CMAPSS-Jet-Engine-Simulated-Data/ff5v-kuh6/about_data
* Accompanying paper here: https://ntrs.nasa.gov/api/citations/20090029214/downloads/20090029214.pdf

This notebook will just be using "FD001" dataset. This dataset has the following qualities -
* engines in train set: 100
* engines in test set: 100
* operating conditions: 1 (sea level)
* fault modes: 1 (hpc degradation)
