Github Link:
https://github.com/sunayanahubli/Comp5520_FoundationsInDigitalHealth_Projects/tree/main/Project_02

Approach:

Steps 1 to 3: Indexing 
Code in notebook: 'IndexMimic_UsingPySolr.ipynb'

1. Download the mimic csv files: notevents.csv, admissions.csv and Diagnosis.csv
2. Read the files using pandas and then index it using pysolr. Use admission ID to fetch the appropriate data from the above three csv/tables
3. After indexing is completed, we will have records that contain following fields:      
	 "id":"",-->row id
        "hadm_id"

        "chartdate"

        "category"

        "icd_codes"

        "expiry_flag":

        "text":

Steps 3 to 7: Serching 
Code in notebook: 'app.ipynb'
4. For the search engine Flask and html javascript is used. 

5. Using mysql I connected to the umls db (the one set up for the cs departmen at 172.16.34.1) to fetch synonyms for search text enterd by used 
6.  User can enter Hospital Expiry Flag, text, date range, icd codes as search input. 

7.  Search is done using pysolr 

Results/Samples are in the folder: ScreenshotsAndSchema