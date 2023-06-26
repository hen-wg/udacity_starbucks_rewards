# Udacity Starbucks Rewards Project
This project forms part of the [Udacity Data Science nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025?utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_term=143524484639&utm_keyword=udacity%20data%20science_p&gclid=Cj0KCQiA5NSdBhDfARIsALzs2EAHpUX_4D3aZrBcu_PbklsCJYBWFEupJ-i6mpiKLVpCNy_7u8hDLVoaAje4EALw_wcB). 

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.The aim of the project was to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. Specifically, a predictive model was built that to predict if a user will that has viewed an offer will complete the offer based on the user demographics and offer details. Various data cleaning and transformation steps were performed to get the data ready for modeling.

An XGBoost model was produced that predicted if an offer will be completed with an F1-score of 72%. Alternative models may be tested to increase model performance. Future work may also include analysing which customer demographic groups have the highest transaction values. This may be useful to see which offers these users respond to best.

More information is published on the post on [Medium](https://medium.com/@henriettewevell/de882cfdfdb0)

# Project Folders and files
Please see below a description of each of the folders and files of interest.                                       

## Analysis
- This folder is for analysis and information only and can be ignored.

## Data                                               
- Contains the input data for the project(transaction, demographic and offer data). 
- Output data will be written to this folder but not committed to git. 

## Other files    
### Notebook files
- 0.Info: information about the project
- 1.EDA_notebook: general exploration and data analysis
- 2.Data_preprocessing: notebook for data preparation and cleaning
- 3.Data_Modeling: notebook for data modeling and interpretation


## Installation process
This project uses remote development through [Windows Subsystem for Linux 2](https://docs.microsoft.com/en-us/windows/wsl/install) , or running natively from Windows. The environment is controlled using `venv` and `pip` for package management.

In order to get the project up and running, open a terminal window and run the following commands:

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Testing
Testing and code modularization was beyond the scope of this tutorial but may be included for future work.