[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NCEI-NOAAGov/data-tour-notebooks/blob/github/)

# PTE Data Tour Notebooks
Python notebooks for interacting with and visualizing the U.S. Precipitation Time Series Explorer (PTE) dataset from the National Centers for Environmental Information (NCEI) using Python.

## Background
These notebooks utilize the PTE dataset to obtain hourly precipitation accumulation data for both historical and in near real-time. The Case Study notebook uses Hurricane Helene in North Carolina in 2024 as an example to introduce users to the dataset and how to interact with the data. The Data Access notebook is a comprehensive tool to conduct single and simultaneous multi-location queries for any location in the U.S. The extracted data can be used to show the likelihood of precipitation exceeding specified thresholds, along with the frequency and risk of extreme rainfall events in a specific region or location. Data can be downloaded in CSV, Parquet, and PNG formats.

The PTE product, which also provides direct data access via the [AWS bucket](https://noaa-mrms-parquet-pds.s3.us-east-1.amazonaws.com/index.html), is available through the National Center for Environmental Information [NCEI](https://www.ncei.noaa.gov/products/precipitation-time-series-explorer/).

## Usage
These notebooks are designed to be run in Google Colab. Clicking the "Open in Colab" button at the top of this README will launch a Google Colaboratory environment in your browser. You can choose which notebook to open. If you do not see the notebook you are interested in, you may need to change the branch using the dropdown menu. You can open, run, and modify these notebooks. You may also download these notebooks from GitHub to your local machine and upload the notebooks to your Google Colab account.

You can also run these notebooks from your local machine or in another notebook environment. Please read through the notebooks before running in a different environment to determine if anything needs to be modified for the notebooks to operate properly.

## Maintainers
industryproving.grounds@noaa.gov

## Contributing
Find a problem with the notebooks? [Open an issue!](https://github.com/NCEI-NOAAGov/data-tour-notebooks/issues/new)

## License
The United States Department of Commerce (DOC) GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. DOC has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any claims against the Department of Commerce stemming from the use of its GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
