[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jscheidtmann/guiding-pynb/HEAD)

# Jupyter Notebooks on Guiding

This repository contains Jupyter Notebooks with calculations and visualizations on Guiding, a technique to improve tracking of a telescope in deep sky photography.
The notebooks contain a mix of English and German language. 

The main files are: 

* A try to leverage Fast Fourier Transformation to see effects of spider vanes [FFT.ipynb](FFT.ipynb)
* Resolution & Seeing Visualization [Guiding.ipynb](Guiding.ipynb]
* Simulate PE curves and generate GuidLog output [GuidingGraphs.ipynb](GuidingGraphs.ipynb)
* Read infos from SubframeSelector (PixInsight) and Session Metadata Plugin (N.I.N.A.) and do statistical analysis on it [PictureStats.ipynb](PictureStats.ipynb)
* Simulate Seeing and compare to drift and periodic error components [SignalAnteile.ipynb](SignalAnteile.ipynb)
* Given a periodic error, how long does it take to cross a pixel [UnguidedPerformance.ipynb](UnguidedPerformance.ipynb)