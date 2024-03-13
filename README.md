## Garbage images classification

We aim to make a Neural network, to clasify garbage images, and based on our trained neural network, to predict the type of garbage from new images.
Initially we will do a multy class classification than we can upgrade it to multy label classification.

To install the project you need to install miniconda locally then you need to do the following actions:

minicoda source: https://docs.anaconda.com/free/miniconda/miniconda-install

1. Create the conda environment - this will create an environment based on what you have in 'environment.yml' file
   command:  conda env create -f environment.yml

2. Activate the environment 
   command: conda activate 'env-name'

3. Optionally you can export your dependencies to an external requirements.txt file
   command: conda list --export > requirements.txt     

4. To update dependencies use the update command and --prune flag to remove all other dependencies that are not longer defined in the .yml file
   command: conda env update -f environment.yml --prune


For this project I named my env:  **image-classification-env**  and I used conda to activate it using the following command:
   command: conda activate image-classification-env
   