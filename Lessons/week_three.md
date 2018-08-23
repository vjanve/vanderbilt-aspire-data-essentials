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
