# Jumia-Deals-website-scraping-and-data-cleaning
Jumia Deals website data scraping with python and data cleaning


 ## About Jumia
* Jumia is the largest online retail store in Kenya. Country-wide Delivery in Kenya.
* 1 in Kenya online retailer and is present in Morocco, Egypt Uganda and many other African countries.


# :dart: Scraping Goals
## Get :->

1. **insight into pricing data** 

2. **insight into market dynamics and analysis** 

# :toolbox: libraries used
1. pandas
2. BeautifulSoup
3. matplotlib
4. seaborn


 # Repository Map
1. :ballot_box_with_check: clean_jumia_deals_In_Kenya.csv - the cleaned scrape data fro jumia
2. :ballot_box_with_check: jumia website scraping.ipynb - the jupyter notebook containing all the scrape code.
3. :ballot_box_with_check: jumia website analysis.ipynb - the jupyter notebook containing all analysis and visualization code. 
4. :ballot_box_with_check: README.md

# Inspiration
**Why this scrapin and analysis ?**

1. **insight into pricing data** 

2. **insight into market dynamics and analysis** 

# Data scraping
  **Refer to the jupyter file ie jumia website scraping.ipynb to see,interact with the code and follow scraping process** 

 # Data cleaning process 
# DATA CLEANING WITH GOOGLE SHEET
These are general guidelines I used in data cleaning

<details><summary>## steps used in data cleaning</summary>
- ## STEP 1: DATA PROFILING
*First things first. study the data to determine what methods of cleaning to do.

- ## KEY PROBLEMS TO LOOK OUT FOR
* Misformatted data
* Text encoding artifacts
* Delimiter and offset issues
* Missing Data
* Null Values
* Unstructured data
* Partial or incomplete values
* Duplicates

- ## STEP 2 : REMOVING NON-PRINTING CHARACTORS
* I made use of the trim, clean, and substitute functions to get rid of these unwanted and non-printing characters.
* ![USE OF TRIM IN DATA CLEANING](https://george.m.ndichu.ltd.co.ke/media/github/JTRIM.png "USE OF TRIM IN DATA CLEANING")

- ## STEP 3: GET RID OF UNNECESSARY SPACING
* Removed unnecessary spacing and adhere to the uniform pattern of spacing
* ![GET RID OF UNNECESSARY SPACING](https://george.m.ndichu.ltd.co.ke/media/github/JTRIM2.png "GET RID OF UNNECESSARY SPACING")

- ## STEP 4: CONVERT 'TEXT-NUMBERES' TO NUMBERS
* some numbers might be stored as text and this could be an issue
* ![GET RID OF UNNECESSARY SPACING](https://george.m.ndichu.ltd.co.ke/media/github/jcolumnf.png "GET RID OF UNNECESSARY SPACING")

- ## STEP 5: CORRECT CASES IE UPPER AND LOWER CASES
* To ensure a professional and clean appearance Correct Use of Cases
* ![CORRECT CASES IE UPPER AND LOWER CASES](https://george.m.ndichu.ltd.co.ke/media/github/jCASE.png "CORRECT CASES IE UPPER AND LOWER CASES")

- ## STEP 6: PARSE DATA TO COLUMNS
* This is for data crammed into a single spreadsheet cell
* ![PARSE DATA TO COLUMNS](https://george.m.ndichu.ltd.co.ke/media/github/jsplit.png "PARSE DATA TO COLUMNS")

- ## STEP 7: USE THE @CONCATENATE and @SPLIT fUNCTIONS TO RESTRUCTURE RECORDS to
* These two functions are super-handy if you have data that needs to be split or combined. @CONCATENATE will create a single column from multiple columns and values, you can even insert text in between the concatenated values

- ## STEP 8: GET RID OF DUPLICATES
![GET RID OF DUPLICATES](https://george.m.ndichu.ltd.co.ke/media/github/JTRIM2.png "GET RID OF DUPLICATES")
</details>
 # ANALYSIS FINDINGS
**insight into pricing data** 
* Prices are higher in major towns especialy in Nairobi
* There are more products and services posted online in Nairobi as compared to other locations.
* In relation to time, products and services and frequenlty posted in big towns as compared to small towns.
* In relation to location and prices , high priced goods are posted in major towns 
 
