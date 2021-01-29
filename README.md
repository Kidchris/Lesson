this is a huge of codes for my training on data science. 
the datasets are too large so for better use i wont import dataset
it's compose of may dataset and the most heavy is the dataset of cars which is 1Go




# SUPERVISED LEARNING

## Analysis of bank_churners 


### EXPLORATORY DATA ANALYSIS 

- data types = *qualitatives features : 6* , *quantitatives features : 17*
- SHAPE :  10127 rows , 23 features   
*there is no target here , so we have to group data in two cluster*
- MISSING VALUES : No missing values
- FEATURES : here the most users are mainly women
    - most people who attirted the company are commonly using blue cards
    - most pleople who are in the company uses also blue cards
    - some features have some outliers and the most importants are Total_Amt_Chng_Q4_Ql and Total_Ct_Chng_Q4_Ql and at last Costumer_Age
    - also we can try to remove the feature named : 'CLIENTNUM' becauseof no importance
    
- 
### The target is here "Attrition_Flag"
- we gonna predict wich group future client will belong. 
This is my first classification solution. 