# CodingLab-sessions

### Creating and checking environments
- To create a new environment named `codinglabenv`, that uses python version 3.5 specifically (if you leave out `python=3.5` conda installs the same Python version you used when you downloaded and installed Anaconda):

`conda create --name codinglabenv python=3.5`

- To activate the environment named `codinglabenv`:

`conda activate codinglabenv`

- To deactivate the environment and return to the `base` environment:

`conda activate`

- To display a list of all environments (the artrisk* indicates the active environment):

`conda info --envs`

### Installing packages in environments
- To check the installed packages within the activated environment:

`conda list`

- To install a particular package in the activated environment, in this case the package `numpy`:

`conda install numpy`

- To install a list of packages in a requirements file, navigate to the file directory and install them: 

`cd [local directory]\notebooks\`

`pip install -r requirements.txt`
