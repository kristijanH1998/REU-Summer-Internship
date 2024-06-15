# Helium Network Blockchain Data Analysis
Big data mining research project for Cybersecurity Research in a Multidisciplinary Environment internship program (Old Dominion University, Summer 2022)

## Table of Contents
- [Description](#description)
- [How to Set up Programming Environment](#how-to-set-up-programming-environment)
- [](#)
- [Research Paper, Presentation,...](#)

## Description
#### Overview and Technologies used
* Big Data mining and in-depth research on economic demand and network traffic of the Helium Network, a disitributed and decentralized Internet of Things (IoT) network, which runs on a digital ledger of transactions called the Blockchain, with native cryptocurrency abbreviated as "HNT". Since Helium Blockchain is a public blockchain, data on all past transactions on the network is visible to the public
* This research uses Python scripts with HTTP requests to Helium Blockchain API to access the Blockchain's database and collect data on network traffic and HNT cryptocurrency data mining statistics, to study Helium network's dynamics, economic supply and demand
* Programming environment chosen for this project was Anaconda with Jupyter Notebook, while Python was selected as the most suitable language
* Requests library was used to send HTTP requests to fetch data from the blockchain, Matplotlib library was used to represent the data in either numerical tables or visually as graphs, Numpy library helped with its tools for array manipulation, JSON was used to store data in a readable form, Time and Datetime libraries were utilized to work with time parameters, and finally Pickle was used for converting output objects into byte streams, stored in .pkl files for further analysis
* The demand for the Helium network’s coverage was analyzed by observing two relevant variables: HNT rewards to hotspots for various network services, and overall data traffic on the network


#### Challenges faced during development

#### Future Research

#### Motivation

#### Things I learned

## How to Set up Programming Environment
1. Follow instructions on [this](https://github.com/git-guides/install-git) link to install Git
2. Choose the location (directory) for the project repository, navigate to it with 'cd [directory-name]' terminal command and inside of it clone the project repository by running the command 'git clone https://github.com/kristijanH1998/REU-Summer-Internship.git' in your terminal
3. Install Jupyter Notebook. Follow instructions on [this link](https://jupyter.org/install)
4. Jupyter Notebook automatically comes with default IPython Kernel available, but to use kernel for different Python version (such as Python 2 or 3), follow instructions for kernel installation and integrating it with Jupyter Notebook specified [here](https://ipython.readthedocs.io/en/latest/install/kernel_install.html#installing-the-ipython-kernel)
5. Install libraries required by the project: NumPy, Matplotlib, and Requests libraries for Python
6. Run Jupyter Notebook with command 'jupyter notebook' and select the .ipynb file from the repository directory with scripts you want to test by running their corresponding cells. Note: The Helium Blockchain API used as a data ledger for this project was retired on July 28, 2023. This essentially means that any script in this repository that contains an HTTP request sent to "https://api.helium.io/" will fail to fetch desired data, since this API does not exist anymore. More information on this change by Helium can be found [here](https://docs.helium.com/solana/migration/blockchain-api/). However, any script that uses data only from .pkl and/or .dat files (and contains no API calls to the Blockchain) can still be run for testing purposes (this stored data from the Blockchain was collected in the summer of 2022 for research purposes and saved in .pkl or .dat formats)

## Research Paper, Results

## Credits