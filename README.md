**[summary](#summary) | [setup](#setup) | [resources](#resources) | [license](#license)**

# Exploring the physics of DC resistivity

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ubcgif/2025-sustech-ess214/main)
[![License](https://img.shields.io/github/license/ubcgif/2025-sustech-ess214.svg)](https://github.com/ubcgif/2025-sustech-ess214/blob/main/LICENSE)

## Summary

This notebook "app" is designed to let users explore the fundamental physics of DC resisivity.


## Setup

There are a few things you'll need to use this app:

1. A working Python installation. I recommend using [Miniforge](https://github.com/conda-forge/miniforge), but you can also use [Anaconda](https://www.anaconda.com/download)
2. To install the [conda environment](./environment.yml)
3. A web browser that works with Jupyter
   (basically anything except Internet Explorer)

**Windows users:** If you ar using Anaconda, when you see "*terminal*" in the instructions,
this means the "*Anaconda Prompt*" program for you.

### Step 1: Python

Install Python on your machine. I recommend using [Miniforge](https://github.com/conda-forge/miniforge), but you can also use [Anaconda](https://www.anaconda.com/download)

If you are looking for tutorials, you can take a look at these videos:
for [Windows](https://youtu.be/FdatS_NKVrM)
and [Linux](https://youtu.be/3ncwbHyZeAg)

This will get you a working Python 3 installation with the `conda` package
manager. If you already have one, you can skip this step.

### Step 2: Download the SimPEG tutorials

To access the notebooks, there are 3 options (in order of preference):
1. You can download a zip file containing https://github.com/ubcgif/2025-sustech-ess214/archive/refs/heads/main.zip.
2. You can run the notebooks online with binder through: https://mybinder.org/v2/gh/ubcgif/2025-sustech-ess214/main

If you download the zip file, unzip it, and then open up a terminal in the `2025-sustech-ess214` directory.

### Step 3: Create the conda environment

With an open terminal in the `2025-sustech-ess214` directory, create the `2025-sustech-simpeg` conda environment using the following. If you have a recent Mac, with an M1 or M2 chip, replace `environment.yml` with `environment-mac.yml`:
```
conda env create -f environment.yml
```
and activate the environment
```
conda activate 2025-sustech-simpeg
```

### Step 4: Launching the notebooks

Once you have activated the conda environment, you can launch the notebooks
```
jupyter lab
```
Jupyter will then launch in your web-browser.

## Resources

**Resources on SimPEG**
- [Docs](http://docs.simpeg.xyz/)
- [Mattermost chat](https://mattermost.softwareunderground.org/simpeg)

**Resources on Geophysics and Inversions**
- [Geophysics for Practicing Geoscientists](https://gpg.geosci.xyz/)
- [EM GeoSci](http://em.geosci.xyz/)
- Lectures from EOSC 350: Exploration & Environmental Geophysics ([2017](https://www.youtube.com/watch?v=C1U2okdfMbU&list=PLd9tNwsUm9jOhbLqjhjDW6ASqwRJtHTb5), [2018](https://www.youtube.com/watch?v=7kFPNooixyw&list=PLd9tNwsUm9jPrWrpdg1JHLieKrzK5w8_-))
- DISC 2017 lectures ([Mexico City](https://www.youtube.com/watch?v=uCnfWXWs5MM&list=PLd9tNwsUm9jM8GWLJm7XLLrE9PYuK-ca2))


## License

All code and text in this repository is free software: you can redistribute it and/or
modify it under the terms of the MIT License.
A copy of this license is provided in [LICENSE](LICENSE).
