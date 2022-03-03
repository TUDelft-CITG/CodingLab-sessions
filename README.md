# CodingLab-sessions

Welcome to the CodingLab-sessions repository! Here, we will share notebooks and other materials that we have used in our CodingLab demo's. 

Below, you find some general information about creating an environment, and installing the required packages, that you need for running CodingLab notebooks in the 'tutorials' folder. 

## Available topics 
Tutorial notebooks are available for the following topics: 
- 20-01-2022: Creating environments, installing packages, cloning a Github repository 
- 20-01-2022: Analysing COVID-19 numbers using public data 

Upcoming: 
- 03-03-2022: From script to package: developing your code 
- 03-03-2022: Working with Pandas / DataFrames

## Useful preparations info
To run the tutorials, you need to clone this Github repository and set up a virtual conda environment on your computer. Here is some info to help you do this. 

### Cloning this Github repository 
If you don't have a clone of this repository yet, you can create this by: 
- Open a command window (Windows) or Terminal (Mac)
- Navigate to the folder where you want to store this repository, using `cd <path>`
- The URL of this repository is: https://github.com/TUDelft-CITG/CodingLab-sessions.git
- Type `git clone <URL>` where URL is the above github repository address 
- A clone of this repository has been created! 

If you have already made a clone of this repository, you can synchronise it such that the latest notebooks will be copied to your computer by: 
- Open a command window (Windows) or Terminal (Mac)
- Navigate to the folder where you have stored this repository, using `cd <path>`
- Type `git pull`
- Your local copy of the repository will be updated. 

### Creating an environment and installing packages in it
In principle, every notebook indicates the steps to take to accomplish this, and the packages that you require to install. Below information is for reference. More 

- To create a new environment named `codinglabenv`, that uses python version 3.9 specifically (if you leave out `python=3.9` conda installs the same Python version you used when you downloaded and installed Anaconda):
`conda create --name codinglabenv python=3.9`
- To activate the environment named `codinglabenv`:
`conda activate codinglabenv`
- To deactivate the environment and return to the `base` environment:
`conda deactivate`
- To display a list of all environments (the displayed artrisk indicates the active environment):
`conda info --envs`
- To check the installed packages within the activated environment:
`conda list`
- To install a particular package in the activated environment, in this case the package `numpy`:
`conda install numpy`
- To install a list of packages in a requirements file, navigate to the file directory and install them: 
`cd [local directory]\notebooks\`
`pip install -r requirements.txt`
- To directly create an environment out of a given textfile `environment.yml`: 
`conda env create -f environment.yml`
