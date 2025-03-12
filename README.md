# Classifying Images of Chicken, Dog and Spider ✨

## Data
**Data Source :**  
The data contain 10 animals images. Since we are interested in classifying images of Chicken, Dog and Spider, we will delete the other images.  

## Data Preprocessing
Chicken images are less compare to Dog and Spider images. We will do image augmentation to the chicken images to make dataset balance by randomly rotate and flipped.

## Setup Environment - Anaconda
```
conda create --name mla python=3.9
conda activate mla
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir submission
cd submission
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard-did.py
```
