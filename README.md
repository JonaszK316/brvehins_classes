# brvehins_classes
A repo with next brvehins dataset build based on data from Autoseg website

# Installation
To set up this project follow below steps:

0. Clone the repository.
```sh
git clone website.git
cd brvehins_classes
```
1. Create the conda enviroment from the 'enviroment_h2O.yml' file
```sh
conda env create -f enviroment_h2O.yml
```
2. Activate the enviroment:
```sh
conda activate brvehins_h2O_en
```
3. Install the project in editable mode so changes in src/ are automatically picked up:
```sh
pip install -e .
```
4. Now one can import your local functions to notebooks like:
```sh
from my_package.helpers import sigmoid
```

# Data
The data for this project are stored in...

# Purpose 
