[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NCEI-NOAAGov/data-tour-notebooks/master) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NCEI-NOAAGov/data-tour-notebooks)
# Data Tour Notebooks
Jupyter notebooks for exploring environmental datasets from the National Centers for Environmental Information (NCEI) using Python.

## Table of Contents
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background
Data Tour Notebooks are Jupyter notebooks created to provide Python-based guided tutorials for accessing and using NOAA data from NCEI servers. Each notebook will focus on a different product and demonstrate basic tools for loading and working with the data. These notebooks are built on conda environments and can be used by either loading a JupyterHub environment in Binder, Google Colaboratory environment, or cloning the notebooks to your machine.

## Install
Using Binder or Colaboratory does not require installation. Cloning this repository will copy all of the Data Tour Notebooks and supporting files to your machine. You will need to already have [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed, and you must install the required packages into a new Conda environment called `ncei` using `environment.yml`.
```
conda env create -f environment.yml
``` 

## Usage
### 1. Binder
Clicking the "Launch Binder" button at the top of this README will launch a Jupyterhub environment in your browser with all of the required packages preinstalled. In this environment, you can open, run, and modify all of the included Data Tour Notebooks, as well as create your own.
### 2. Colaboratory
Clicking the "Open in Colab" button at the top of this README will launch a Google Colaboratory environment in your browser. As in Binder, you can open, run, and modify any of the included Data Tour Notebooks. You may need to manually install the `cartopy` and `netCDF4` packages.
 ```
!apt-get -qq install python-cartopy python3-cartopy
!pip install netCDF4
```

### 3. Local repository
This repo must be installed before using locally. Activate the conda environment, and open Jupyter notebooks.
 ```
conda activate ncei
jupyter notebok
``` 

## Maintainers
[@markccapece](https://github.com/markccapece)

## Contributing
Find a problem with the notebooks? [Open an issue!](https://github.com/NCEI-NOAAGov/data-tour-notebooks/issues/new)

## License
The United States Department of Commerce (DOC) GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. DOC has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any claims against the Department of Commerce stemming from the use of its GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government
