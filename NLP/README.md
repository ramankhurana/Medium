## set up conda environment 
conda create --name medium-nlp  python=3.8

## make sure jupyter notebook can see the env you created 
conda install nb_conda

jupyter nbextension install --user --py nb_conda
jupyter nbextension enable --user --py nb_conda


## Install required python packages 
pip install pandas
pip install sklearn
pip install nltk
