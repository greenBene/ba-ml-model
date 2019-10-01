# Transportation Mode Classificatin for Bachelor thesis

In this project I train two different machine learning models, a XGBoost Classifier and a Multilayer Perceptron Classifier, to distinguish between the two transportation modes walking and dricing (a car). 

## Setup
0. Install Jupyter Notebook (https://jupyter.org/install.html)
1. Download the GoLife Dataset 1.3 (https://www.microsoft.com/en-us/download/details.aspx?id=52367) 
2. Extract its data into the folder `./geolife-data/` on the main folder of this project. The 'Data' folder needs to be in `./geolife-data/Data/`. 
3. Create the empty folder `./geolife-data/Prepared/`

## Run
1. Run the notebook `data-preparation.ipynb`
2. Run the notebook `feature-extraction and preprocessing.ipynb`
3. Run the training notebooks `XGBoost-training.ipynb` or `MLPClassifier-training.ipynb`
