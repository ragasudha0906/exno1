# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

### Coding and Output
## 1.Import Required Libraries
<img width="1347" height="151" alt="ds1" src="https://github.com/user-attachments/assets/6358add8-fbe3-40be-9fe0-8612a272278f" />

# 2.Load Dataset
       
 <img width="1322" height="671" alt="ds2" src="https://github.com/user-attachments/assets/6cc0110f-6fac-4245-8f2b-de9bad40e984" />

# 3.Data Cleaning
# Check for null value

<img width="1336" height="281" alt="ds3" src="https://github.com/user-attachments/assets/c8266b36-d9bb-4a08-8901-02c4cb806dde" />


# Handling missing values
   <img width="1338" height="80" alt="ds4" src="https://github.com/user-attachments/assets/a28c1b9e-9e2b-4c44-a13e-67744ea13de3" />


# Remove duplicates
  <img width="1341" height="121" alt="ds5" src="https://github.com/user-attachments/assets/5fed6609-cc3a-4da0-b713-6bdf20ef5b3b" />

# Check data types
   <img width="1336" height="361" alt="ds6" src="https://github.com/user-attachments/assets/8d74e90e-bb33-46fb-b437-fb22227ce4d5" />


# 4.Outlier Detection

# IQR Method
<img width="1347" height="477" alt="ds9" src="https://github.com/user-attachments/assets/2eae7f6a-a600-4c0e-8176-87d3210066ed" />


## Z-Score method
<img width="1337" height="342" alt="ds7" src="https://github.com/user-attachments/assets/26e5b3d7-81a8-4945-9b39-2bdf3d163fd9" />

# Outlier removal
<img width="1241" height="142" alt="ds10" src="https://github.com/user-attachments/assets/672573ea-cebe-46bd-be31-84c426a1e641" />

# Visualization (Boxplot)

<img width="1347" height="863" alt="ds8" src="https://github.com/user-attachments/assets/1f83cc82-2cf3-4910-85eb-983206b211b3" />


# Result
 In this experiment, we carried out data preprocessing and outlier detection on a dataset. First, the required libraries were imported and the dataset was loaded. Data cleaning was performed by checking and handling missing values, removing duplicates, and verifying data types. Outliers were detected using the IQR method and Z-score method, then removed to improve data quality. Finally, a boxplot was used to visualize the outliers, ensuring the dataset was clean and reliable for further analysis.
