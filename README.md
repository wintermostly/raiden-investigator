# Raiden Investigator

A Jupyter notebook that analyzes on-chain channel data from the Raiden Network collected by the [Raiden Datacollector](https://github.com/wintermostly/raiden-datacollector).

This notebook was programmed to serve a master's thesis covering blockchain data analysis. Its aim is to analyze available on-chain channel data about the Ethereum-based second layer network Raiden from the exported channel information of a .csv database. It utilizes the pandas library to sort and analyze channel information and uses matplotlib, seaborn and pyvis for visualization.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

It is recommended to make use of Python environments to install this software. A Miniconda installation has proven to be sufficient and can be found [here](https://docs.conda.io/en/latest/miniconda.html).

```
# Create an empty environment with name myenv
conda create -n myenv python

# Activate the environment
conda activate myenv

# Update Python to a current version
conda update python
```

Required Software packages

```
python 3.6
pandas 1.0.1
jupyter notebook 6.0.3
matplotlib 3.1.1
seaborn 0.10.0
pyvis 0.1.3.1
```

### Installing

Install Jupyter notebook for having the basic framework available through conda or another method outlined [here](https://jupyter.org/install).

```
# Install Jupyter notebook 
conda install -c conda-forge notebook
```

Install pandas package for data handling via pip or another method outlined [here](https://pandas.pydata.org/docs/getting_started/install.html).

```
# Install pandas package with conda or pip command
conda install pandas
```

Install matplotlib package for visualization through conda or another method outlined [here](https://matplotlib.org/3.1.1/users/installing.html).

```
# Install matplotlib package with conda
conda install matplotlib
```

Install seaborn package for visualization through conda or another method outlined [here](https://seaborn.pydata.org/installing.html).

```
# Install seaborn package with conda
conda install seaborn
```

Install pyvis package for network analysis and visualization via pip or another method outlined [here](https://pyvis.readthedocs.io/en/latest/install.html).

```
# Install pyvis package via pip command
$ pip install pyvis
```


## Deployment

Clone the project on your deployment system of choice.

Start Jupyter Notebook, load the .csv database in this repository or use an updated database built by the [Raiden Datacollector](https://github.com/wintermostly/raiden-datacollector) repository.

```
# Start Juypter Notebook
jupyter notebook
```
Modify all cells and commands as needed.

## Built With

* [Sublime Text](https://www.sublimetext.com/) - Text editor for development
* [Sublime Merge](https://www.sublimemerge.com/) - Git client
* [Miniconda](https://docs.conda.io/en/latest/miniconda.html) - Python package manager
* [Jupyter Notebook](https://jupyter.org/) - Data science suite

## Authors

**Christian Winter** - *Initial work for master's thesis* - [wintermostly](https://github.com/wintermostly)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
