# 🦠 FBA_OLISSIPO_Winter_School 🧬
 

[![DOI](https://zenodo.org/badge/740951705.svg)](https://zenodo.org/doi/10.5281/zenodo.10634715)

## 📜 About

This repo hosts training materials for the [OLISSIPO Winter School]([https://www.sysbiol.cam.ac.uk/Part%20III](https://www.inesc-id.pt/events/6839/)) Mathematical modelling of inter-cell and communities’ interactions with a focus on metabolism. More specifically, these are practical exercises for the computational session on flux balance analysis (FBA) using genome-scale metabolic models (GEMs). Some of the text and code chunks in the following exercises are based on selected portions of the [cobrapy documentation](https://cobrapy.readthedocs.io/en/latest/).

### Learning outcomes

#### [Exercise 1](https://github.com/arianccbasile/FBA_OLISSIPO_Winter_School/blob/main/systems-biology-fba-practical-main/notebooks/1_fba.ipynb)
- **1.1**: Import a metabolic reconstruction
- **1.2**: Inspect the reactions of your model
- **1.3**: Inspect the metabolites in your model
- **1.4**: Inspect the genes in your model
- **1.4.1**: Perform in-silico gene knockout experiments

#### [Exercise 2](https://github.com/arianccbasile/FBA_OLISSIPO_Winter_School/blob/main/systems-biology-fba-practical-main/notebooks/2_fba.ipynb)
- **2.1**: Modify growth medium of your reconstruction
- **2.2**: Perform gene essentiality analysis under different conditions
- **2.3**: Case study, simulate the Crabtree effect in yeast

#### [Exercise 3](https://github.com/arianccbasile/FBA_OLISSIPO_Winter_School/blob/main/notebooks/3_fba_community.ipynb)
- **3.1**: Build a 2 members community
- **3.2**: Perform community-based simulations
- **3.3**: Basics of pandas to analyse exchanges
- **3.4**: Modify growth medium of your community

## 🚚 Software requirements

Please install these packages on your own laptop if required:

* [cobrapy](https://opencobra.github.io/cobrapy/)
* [matplotlib](https://matplotlib.org/stable/)
* [numpy](https://numpy.org/install/)
* [notebook](https://jupyter.org/install#jupyter-notebook)
* [micom](https://micom-dev.github.io/micom/index.html)
* [pandas](https://anaconda.org/anaconda/pandas)
* os

To install on your own computers use the [pip package manager](https://pip.pypa.io/en/stable/getting-started/).

Using the `requirements.txt` files:

```
$ pip install -r requirements.txt
```


## 🛠️ Usage

You will find everything you need for these practical exercises under the `/notebooks` folder. Each tutorial is uploaded as `.html`, `.md`, `.tex`, and `.ipynb` files. As you carry out the exercises using the the python notebooks, you will find the original text and results in the html, markdown, and latex files. 

### Running locally

You may run these exercises on your local machine by cloning this repo:

```
$ git clone https://github.com/arianccbasile/FBA_OLISSIPO_Winter_School/tree/main
```

Navigate into cloned repo folder:

```
$ cd FBA_OLISSIPO_Winter_School
```

Launch interactive jupyter notebook session:

```
$ jupyter notebook
```

This should launch a browser window, where you can click on the `/notebooks` folder and start the exercises.


## 🧠 Further exercises

* [SymbNET](https://github.com/franciscozorrilla/SymbNET): From metagenomics to metabolic Interactions 
* [EMBOMicroCom](https://github.com/franciscozorrilla/EMBOMicroCom): Metabolite and species dynamics in microbial communities


## 👷 Contributors

* Originally developed by Arianna Basile and Kiran Patil in 2023
* Updated by Francisco Zorrilla and Arianna Basile in 2024
* Community modelling added by Arianna Basile in 2024


## ☎️ Contact

Feel free to get in touch with us by raising an issue or sending an e-mail to Arianna Basile (ab2851@mrc-tox.cam.ac.uk)
