# Helium Network Blockchain Data Analysis
Big data mining research project for Cybersecurity Research in a Multidisciplinary Environment internship program (Old Dominion University, Summer 2022)

## Table of Contents
- [Description](#description)
- [How to Set up Programming Environment](#how-to-set-up-programming-environment)
- [Research Paper, Poster, Presentation, and Results](#research-paper-poster-presentation-and-results)
- []()

## Description
#### Overview and Technologies used
* Big Data mining and in-depth research on economic demand and network traffic of the Helium Network, a distributed and decentralized Internet of Things (IoT) network, which runs on a digital ledger of transactions called the Blockchain, with native cryptocurrency abbreviated as "HNT". Since Helium Blockchain is a public blockchain, data on all past transactions on the network is visible to the public
* This research uses Python scripts with HTTP requests to Helium Blockchain API to access the Blockchain's database and collect data on network traffic and HNT cryptocurrency data mining statistics, to study Helium network's dynamics, economic supply and demand
* Programming environment chosen for this project was Anaconda with Jupyter Notebook, while Python was selected as the most suitable language due to its high readability and maintainability, good libraries for data analysis, and simplicity of presenting its code to one's audience and communicating it to others
* Requests library was used to send HTTP requests to fetch data from the blockchain, Matplotlib library was used to represent the data in either numerical tables or visually as graphs, Numpy library helped with its tools for array manipulation, JSON was used to store data in a readable form, Time and Datetime libraries were utilized to work with time parameters, and finally Pickle was used for converting output objects into byte streams, stored in .pkl files for further analysis
* The demand for the Helium network’s coverage was analyzed by observing two relevant variables: HNT rewards to hotspots for various network services, and overall data traffic on the network

#### Challenges faced during development
* A significant problem that appeared during the project were computational limits of the personal machine I used at that time to fetch, store, and process all the data I needed to perform my study. Some scripts took entire nights to finish since data for 8 cities over a period of up to 1 year had to be analyzed, and each city's total network transaction data would sometimes take hours to be fully processed. I ended up getting help from my mentor who used another machine (which had more RAM capacity and faster CPU) and fetched the data I needed, stored it as .pkl files, and sent them to me for further analysis
* Another obstacle I experienced in the beginning of this research was having to understand how to use cursor logic within my scripts for sending consecutive HTTP requests to fetch serialized data that came from weeks, sometimes months of transactions between hotspots on the network. This was the only way to fetch all data for entire time intervals that were studied

#### Future Research
* More research on Helium Network’s presence in other regions of the United States and/or other countries could be useful for a more elaborate analysis of Helium’s economics
* It would be insightful to take a deeper look into HNT fluctuation and data traffic over longer time periods for a more methodical economic analysis. Such work could be useful for other students and scholars interested in studying decentralized IoT networks and virtual currencies
* Future research could observe over time if demand for the Helium network increases, and identifying the environmental factors that attribute to miners' success would be very useful

#### Motivation
* I set on a course of this project to gain research experience related to my discipline, and learn more about big data and how data analysis can be performed with the help of programming languages

#### Things I learned
* From this project I learned what things like Blockchain, Internet of Things, Decentralized Networks, Hotspots, Cryptocurrency Mining and other such terms mean and how they relate to what I already know about existing Internet technologies and digital networks
* By conducting this research I got a lot of experience programming in Python, and using its libraries for connecting to external APIs, and to perform data collection, processing, representation, and visualization
* And finally this internship taught me how to write scientific papers, perform scientific inquiry by using digital tools, interpret data collected with observed variables in mind, and draw conclusions about the topic under study

## How to Set up Programming Environment
1. Follow instructions on [this](https://github.com/git-guides/install-git) link to install Git
2. Choose the location (directory) for the project repository, navigate to it with 'cd [directory-name]' terminal command and inside of it clone the project repository by running the command 'git clone https://github.com/kristijanH1998/REU-Summer-Internship.git' in your terminal
3. Install Jupyter Notebook. Follow instructions on [this link](https://jupyter.org/install)
4. Jupyter Notebook automatically comes with default IPython Kernel available, but to use kernel for different Python version (such as Python 2 or 3), follow instructions for kernel installation and integrating it with Jupyter Notebook specified [here](https://ipython.readthedocs.io/en/latest/install/kernel_install.html#installing-the-ipython-kernel)
5. Install libraries required by the project: NumPy, Matplotlib, and Requests libraries for Python
6. Run Jupyter Notebook with command 'jupyter notebook' and select the .ipynb file from the repository directory with scripts you want to test by running their corresponding cells. Note: The Helium Blockchain API used as a data ledger for this project was retired on July 28, 2023. This essentially means that any script in this repository that contains an HTTP request sent to "https://api.helium.io/" will fail to fetch desired data, since this API does not exist anymore. More information on this change by Helium can be found [here](https://docs.helium.com/solana/migration/blockchain-api/). However, any script that uses data only from .pkl and/or .dat files (and contains no API calls to the Blockchain) can still be run for testing purposes (this stored data from the Blockchain was collected in the summer of 2022 for research purposes and saved in .pkl or .dat formats)

## Research Paper, Poster, Presentation, and Results
* The paper I wrote for this research study can be found on (this link)[https://docs.google.com/document/d/1e3eJWykSwqRAiOo_efxFnnfB9gEqLwgV/edit?usp=sharing&ouid=118036694644451906663&rtpof=true&sd=true]
* The poster I made for this project can be found (here)[https://docs.google.com/presentation/d/1L2tvWKAIFjRoeVKj8vxawBlwEcLpBivB/edit?usp=sharing&ouid=118036694644451906663&rtpof=true&sd=true]
* The slides for the final presentation I gave at the end of the internship program can be accessed (here)[https://docs.google.com/presentation/d/1EP9JSGx_IGVwyFztLyxRJESCElC5qrW9DdnMKnJ87qU/edit?usp=sharing]
* Screenshots of some results derived from the study are provided below:
HNT reward statistics for hotspots in Miami, Florida:
![HNT Rewards in Miami, FL](/results-screenshots/odu-helium-analysis4.png?raw=true "HNT Rewards in Miami, FL")

## Credits