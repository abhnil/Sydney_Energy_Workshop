# Sydney_Energy_Workshop_2025
This repository comprises notebooks for the workshop related to using weather and climate data for energy research. 

# Getting Started
The notebooks cover:

- accessing the cmip6 dataset from different data sources.
- accessing regional climate data (rcm) from Australia from NCI.
- plotting key variables from the cmip6 and rcm dataset.
- producing key synergy metrics.

# Testing the code
You can run the code in these notebooks on your own machine without downloading any of the requirements using binder. Note - the code will be much slower on binder than on your own machine. 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/abhnil/Fiji_Energy_Workshop/main)




# Requirements
Clone this repository into your local directory.
```
git clone https://github.com/abhnil/Sydney_Energy_Workshop.git
cd Sydney_Energy_Workshop
```
Install and activate the virtual environment **cmip6env** to run the notebooks using Python 3.
```
python3 -m venv cmip6env
source cmip6env/bin/activate
```
Install the requirements.txt file 
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

# Running Notebooks
```
cd notebooks
jupyter lab <notebook>
```






