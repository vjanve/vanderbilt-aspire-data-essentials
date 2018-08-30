##### Week 2:
Understanding the Question + Getting Data  
- Critical thinking and active questioning  
- Acquiring domain expertise  
- Articulate question  
- Get and begin cleaning data  
- Check original file footnotes and source website to better understand data
- Common data wrangling issues 
- Resources for help with coding 
- Review of code for today (pandas API)  
- Coding Tasks:  
  * `Import pandas as pd`
  *  Create a DataFrame, `hospice_df`, from the hospice CSV file.   
      - Keep only the rows where facilities are in TN.  
      -  Keep only the **Facility Name**, **Address Line 1**, **City**, **State**, **County Name**, **CMS Region**, **Ownership Type**, and **Cerfification Date** columns. Make all column names lower case and without spaces.  
      - Examine the first 5 rows and the last five rows of the TN hospice data.  
     - Print the dimensions of the data. How many hospice facilities are in TN?
  * Create a DataFrame, `cancer_df`, from the cancer CSV file.  
      - Look at the head and tail of the DataFrame.  
      - Print the shape of the cancer data.  
      - Keep and rename all columns. 
      - You can read more about **2020 Healthy People Objective target of 161.4 cancer deaths per 100,000 people** [here](https://www.healthypeople.gov/).
  * Create a DataFrame, `pop_df`, from the census CSV file.  
      -  Look at the head and the tail  
      - Print the shape  