# Installation - generic, but definitely works on Mac M1

This is the instruction set for training module:

GitHub Repository is available at : https://github.com/openalea-training/niab_workshop
Install GitHub so that at least you can run through the command line
Install Miniconda- (I installed Anaconda instead)
For fastest installation, install mamba
conda install mamba -c conda-forge

PULL THE GIT REPO IF YOU WANT TO RUN THE TRAINING
Change into the gihubt directory and ensure that the file environment.yml in the github repo in a file environment.yml is in the directory which you run the following commands from :

Create a new environment :

mamba env create -f environment.yml

Activate the environment using :  

conda activate lpytraining

# If you want your own Conda environment, rather than the training environment

conda install mamba -c conda-forge
conda create -n lsystems openalea.lpy -c fredboudon -c conda-forge 
conda activate lsystems
conda install -c conda-forge jupyterlab
pip install pgljupyter


#use the command below to see packages 
conda list 

# install Vstudio and link in your github account

You need to install juptyper and github addins into vstudio
I installed Jupyter, Jupyter Keymap Jypyter Notebook Renderers Pylance and Python- I don't know if all of this is needed

You can the clone or start the repository within vstudio
You should also be able to see and select the version of python in the conda environment that you want in order to execute code using Lpy

Sidenote- I can't get the PlantGL/Juptyter graphics working in safari- not a big exploration yet, find in chrome

