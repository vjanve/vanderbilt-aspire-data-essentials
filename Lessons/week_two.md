##### Week 2:
Understanding the Question + Getting Data  
- Critical thinking and active questioning  
- Acquiring domain expertise  
- Articulate question  
- Get and begin cleaning data  
- Check original file footnotes and source website to better understand data
- Common data wrangling issues    
- Coding Tasks:  
  * `Import pandas as pd`
  * a) Create a DataFrame, `hospice_df`, from the hospice CSV file.   
  b) Keep only the rows where facilities are in TN.  
  c) Keep only the **Facility Name**, **Address Line 1**, **City**, **State**, **County Name**, **CMS Region**, **Ownership Type**, and **Cerfification Date** columns. Make all column names lower case and without spaces.  
  d) Examine the first 5 rows and the last five rows of the TN hospice data.  
  e) Print the dimensions of the data. How many hospice facilities are in TN?
  * a) Create a DataFrame, `cancer_df`, from the cancer CSV file.  
  b) Look at the head and tail of the DataFrame.  
  c) Print the shape of the cancer data.  
  d) Keep and rename all columns. You can read more about **2020 Healthy People Objective target of 161.4 cancer deaths per 100,000 people** [here](https://www.healthypeople.gov/).
  * a) Create a DataFrame, `pop17_df`, from the census CSV file.  
  b) Look at the head and the tail  
  c) Print the shape  