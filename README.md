# LSTM_classification

Classification of Multi-particle events using LSTM's and Convolutional Neural Networks.

# Data
Generated in Pythia8240
Data is stored in .txt files, where each line represents an event. Each event is comprised of a list of particle variables (pT, eta, phi), which are separated by commas.
The data is split into two folders, ATLAS-like (LHC) and STAR-like (RHIC). Each of those datasets coontaint MinBias (ND), Difr (SD+DD), SinDifr (SD) and DblDifr (DD).

# Neural Nets
2class_conventional.ipynb == rapidity gap dense net for bg/sig classification
2class_LSTM.ipynb == LSTM net for bg/sig classification
3class_conventional.ipynb == rapidity gap dense net for ND/SD/DD classification
3class_LSTM.ipynb == LSTM net for ND/SD/DD classification
