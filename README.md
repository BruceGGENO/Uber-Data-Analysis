# Names: GENO Bruce

# ID: 27193

# INTRODUCTION
## Uber-Data-Analysis
This is a project i did on Uber, a famous multi-national transport company available in 70 countries and about 15,000 cities worldwide. I analyzed it using data i downloaded from Kaggle. I hope you get to learn something from this as I did too. 

# METHODOLODY
### The data that was used was extracted from Kaggle. I was able to extract this uber data from Kaggle. After extracting the data I cleaned it, then used Power Bi to anaylze it as well. I used Anaconda and through it launched Jupyter Notebook for the python codes. 

# ANALYSIS AND RESULTS

## 1. Loading the dataset into a Pandas DataFrame using Python
<img width="954" height="364" alt="1" src="https://github.com/user-attachments/assets/050974bf-fceb-40ae-8b38-6904795613b1" />

##   2. Perform comprehensive exploratory data analysis (EDA) to understand:
• Dataset structure and dimensions

• Data types and variable descriptions
• Initial data quality assessment 
<img width="936" height="530" alt="2" src="https://github.com/user-attachments/assets/5b3206de-ced6-4cb4-9405-caea6de00006" />

## Handle missing values and clean the data for analysis
<img width="941" height="100" alt="3" src="https://github.com/user-attachments/assets/6d0219b3-72a6-40bb-aefa-0625c299c550" />

## Generate descriptive statistics including:
▪ Mean, median, mode, standard deviation
<img width="889" height="338" alt="4" src="https://github.com/user-attachments/assets/84152917-c241-4a59-833d-40d15648764a" />

## Quartiles, data ranges and outlier identification
<img width="952" height="253" alt="5" src="https://github.com/user-attachments/assets/94683112-2073-4b5e-a0f3-4a0e120558a4" />

## . Analysis of relationships between key variables such as
▪ Fare amount vs. distance traveled
<img width="945" height="214" alt="6" src="https://github.com/user-attachments/assets/4d0468aa-ae62-4773-84c9-26afbe292890" />
### Below is the output
<img width="945" height="214" alt="6" src="https://github.com/user-attachments/assets/0f750afd-043f-4e08-8e8b-abfd7facae4a" />

## 3. Feature Engineering
Below there's the codes for analytical features such as:
▪ Hour, day, month extracted from timestamps
▪ Day of week categorization
▪ Peak/off-peak time indicators 
<img width="941" height="249" alt="8" src="https://github.com/user-attachments/assets/4ff2fae9-436d-4145-a20f-396a4ad92433" />

## Here's how to Identify and properly encode categorical variables
<img width="945" height="52" alt="9" src="https://github.com/user-attachments/assets/51d882ee-7f40-444f-8641-154372f5d5ba" />

## After applying the above changes I then saved the enhanced dataset to be used for Power BI import for visuals and analysis
<img width="958" height="45" alt="10" src="https://github.com/user-attachments/assets/9897bcb5-5a77-4da2-af54-53a399bd9d40" />

# CONCLUSION
### As you can see, the first step was to import the original dataset but since it had some missing data, it had to be cleaned for proper analysis. After it was properly cleaned the new data was then put in another file which I named uber_enhanced. I then imported uber_enhanced in Power BI for the visuals through histograms.
