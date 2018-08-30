##### Week 3:
Cleaning Data  
- Approaches and techniques for cleaning data
- Common data wrangling & cleaning issues  
- Hands-on lab to clean, organize data
- Coding Tasks:
    * Work on cleaning and wrangling `pop_df`. 
        - cancer rates begin to climb at age 50 so we are particularly interested in population over 50.
        - In the end, you should have these 31 columns:  
   `'county', 'pop2010all', 'pop2014all', 'pop2017all', 'median_age_2010', 'median_age_2014', 'median_age_2017', 'pop2010_50to54','pop2014_50to54', 'pop2017_50to54', 'pop2010_55to59', 'pop2014_55to59', 'pop2017_55to59', 'pop2010_60to64', 'pop2014_60to64', 'pop2017_60to64',
    'pop2010_65to69', 'pop2014_65to69', 'pop2017_65to69', 'pop2010_70to74', 'pop2014_70to74', 'pop2017_70to74', 'pop2010_75to79', 'pop2014_75to79', 'pop2017_75to79', 'pop2010_80to84', 'pop2014_80to84', 'pop2017_80to84',
    'pop2010_85over', 'pop2014_85over', 'pop2017_85over'.  
            - beginning DataFrame has 95 rows and 993 columns
            - drop all April estimate columns
            - keep only columns that pertain to 2010, 2014, and 2017
    
    * Use an outer join to merge `pop_df` and `cancer` data to a DataFrame called `pop_and_cancer`
    * Use the pandas series `value_counts()` method to create a dictionary called `hospice_per_county`. The key for this dict will be the county name and the value will be the count of hospice facilities in that county. Populate the dictionary for all TN counties by adding the counties with 0 hospice facilities to `hospice_per_county`.
    * Use the dictionary you created, `hospice_per_county` to populate a new column in `pop_and_cancer`. Call this column `hospice_count`.
        
    
