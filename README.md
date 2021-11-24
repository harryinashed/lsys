# Installation - generic, but definitely works on Mac M1

This is the instruction set for models 
GitHub Repository is available at : https://github.com/openalea-training/niab_workshop

Install GitHub Desktop and if you are familiar with git clone the repository niab_workshop. 
Install Miniconda- THOUGH I INSTALLED ANACONDA
For fastest installation, install mamba
conda install mamba -c conda-forge

PULL THE GIT REPO IF YOU WANT TO RUN THE TRAINING
Get the file environment.yml in the github repo in a file environment.yml : https://github.com/openalea-training/niab_workshop/blob/main/environment.yml
Create a new environment :
mamba env create -f environment.yml
Activate the environment using :  
	conda activate lpytraining

# IF YOU WANT YOUR OWN CONDA ENVIRONMENTT

conda install mamba -c conda-forge

#core installation
conda create -n lsystems openalea.lpy -c fredboudon -c conda-forge 
conda activate lsystems

conda install -c conda-forge jupyterlab
pip install pgljupyter


 #use command below to see packages 
conda list 

# install Vstudio and link in your github account

you need to install juptyper and github addins into vstudio
I installed Jupyter, Jupyter Keymap Jypyter Notebook Renderers Pylance and Python- I don't know if all of this is needed

you can the clone or start the repository within vstudio
you shoul also be able to see and select the version of python in the conda environment that you want in order to execute code using lpy

sidenote can't get the juptyter api for graphics working in safari- not a big exploration yet, find in chroms

