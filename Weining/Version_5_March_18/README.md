1. *CountryNodes_All.csv* ---> updated methods to unified country names that contain special characters
2. *EdgeList_All.csv* ---> updated methods to unified country names that contain special characters
3. *v4_Data_Preprocessing.ipynb* ---> updated version to preprocess UN Migration data and WHO influenza data
    - Part I: an automated data pipeline to rand and clean UN migration meta data, generate yearly migration stock data, and calculate migration increase rate for year 2005, 2010, 2015, and 2019.
    - Part II: an automated data pipeline to read and process 165 country's influenza data, and generated new features that match the region name for each country. 
    - When you run this python file, please keep the migration meta data *2019UNData.xlsx*, region label txt files *RegionData* folder, and WHO influenza meta data *Influenza_165* folder in the same directory as this python file.
    - Lastly, please replace the directory path (in Part II, section 5 path = "C:/Users/Win...") with your own path.
4. *UNMigration_v6.Rmd* ---> r markdown file to construct network graph (to be continue)
5. *Plots* folder ---> igraph plots in high resolution
