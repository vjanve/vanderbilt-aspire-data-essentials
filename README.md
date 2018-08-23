### Data Essentials
#### The Question: How do cancer mortality rates, aging populations, and the presence of hospice facilities relate to one another in Tennessee counties?

#### Data Sources - files are located in the `/data/` folder of this repository
 - Hospice data (last updated 08/16/2018) is a comma separated value (CSV) file downloaded from [CMS](https://healthdata.gov/dataset/hospice-general-information)  - `Hospice_General_Information.csv`
  - Population data (2010-2017) is a CSV file downloaded from the [US Census Bureau] (https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml) - `PEP_2017_PEPAGESEX.csv`
  - Cancer mortality 5-year trend (2011-2015) data is a CSV file downloaded from the [National Cancer Institute](https://statecancerprofiles.cancer.gov/deathrates/index.php?stateFIPS=47&cancer=001&race=00&sex=0&age=001&type=death&sortVariableName=rate&sortOrder=default#results) - `cancer_deaths.csv`

##### Week 1:
What is Data Science?  
- Coding Skills/Statistics/Domain Expertise  
- The Data Science Process  
- Examples of Data Science in the world  
- Install Anaconda Navigator (Jupyter Notebook) to prepare for next session  
- Create a GitHub account 
- Review resources and package documentation for help with coding

##### Week 2:
Understanding the Question + Getting Data  
- Critical thinking and active questioning  
- Acquiring domain expertise  
- Articulate question  
- Get and begin cleaning data  
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
  d) Keep and rename these columns: County, FIPS, Met Healthy People Objective of 161.4?, Age-Adjusted Death Rate - deaths per 100,000, . You can read more about 2020 Healthy People Objective target of 161.4 cancer deaths per 100,000 people [here](https://www.healthypeople.gov/).
  * a) Create a DataFrame, `pop17_df`, from the census CSV file.  
  b) Look at the head and the tail  
  c) Print the shape  
   

##### Week 3:
Cleaning Data  
- Common data wrangling & cleaning issues  
- Hands-on lab to clean, organize data
- Coding Tasks:
    * Work to drop extra data from `pop17_df`. In the end, you should have these 61 columns:  
   `'county', 'pop2010all', 'pop2014all', 'pop2017all', 'pop2010_under5',
       'pop2014_under5', 'pop2017_under5', 'pop2010_5to9', 'pop2014_5to9',
       'pop2017_5to9', 'pop2010_10to14', 'pop2014_10to14', 'pop2017_10to14',
       'pop2010_15to19', 'pop2014_15to19', 'pop2017_15to19', 'pop2010_20to24',
       'pop2014_20to24', 'pop2017_20to24', 'pop2010_25to29', 'pop2014_25to29',
       'pop2017_25to29', 'pop2010_30to34', 'pop2014_30to34', 'pop2017_30to34',
       'pop2010_35to39', 'pop2014_35to39', 'pop2017_35to39', 'pop2010_40to44',
       'pop2014_40to44', 'pop2017_40to44', 'pop2010_45to49', 'pop2014_45to49',
       'pop2017_45to49', 'pop2010_50to54', 'pop2014_50to54', 'pop2017_50to54',
       'pop2010_55to59', 'pop2014_55to59', 'pop2017_55to59', 'pop2010_60to64',
       'pop2014_60to64', 'pop2017_60to64', 'pop2010_65to69', 'pop2014_65to69',
       'pop2017_65to69', 'pop2010_70to74', 'pop2014_70to74', 'pop2017_70to74',
       'pop2010_75to79', 'pop2014_75to79', 'pop2017_75to79', 'pop2010_80to84',
       'pop2014_80to84', 'pop2017_80to84', 'pop2010_85over', 'pop2014_85over',
       'pop2017_85over', 'median_age_2010', 'median_age_2014',
       'median_age_2017'`.  
       One possible approach is to drop all the columns that have April data, keep only 2010, 2014, and 2017 data that is **not** gender specific along with `Geography`, rename columns and drop the remaining additional columns (that show aggregate data). 

##### Week 4:
Exploratory Data Analysis
a. Types of data and techniques to explore variables by type
b. Visualizations as a tool for exploration
c. Hands-on lab to create data visualizations and summary statistics

##### Week 5:
Annotation and Reproducibility
a. Using markdown in Jupyter to annotate analyses
b. Importance of reproducibility
c. Hands-on lab exploring data visualization and annotating methods

##### Week 6:
Formulating a Hypothesis about the Data
a. Develop (and execute) a plan to test the hypothesis
b. Introductory overview of machine learning
c. Hands-on lab: pair plots and linear regression

##### Week 7:
Communicating the Results
a. Importance of empathy/know your audience
b. Deliver findings
c. Hands on lab to polish work for presentation

##### Week 8:
Presentation of Project Insights
Resources for Learning More / Building Skills in Data Science
Post-Course Evaluation