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
2. :ballot_box_with_check: jumia website scraping.ipynb - the jupyter notebook containing all the code, all analysis and visualization. 
3. :ballot_box_with_check: README.md

# Inspiration
**Why this scrapin and analysis ?**
1. Understand Product & Market Trends.

# Data scraping 
 **Refer to the jupyter file ie jumia website scraping.ipynb to see,interact with the code and follow scraping process** 
# Data cleaning process 
# DATA CLEANING WITH GOOGLE SHEET
These are general guidelines I used in data cleaning
## steps used in data cleaning
## STEP 1: DATA PROFILING
*First things first. study the data to determine what methods of cleaning to do.

## KEY PROBLEMS TO LOOK OUT FOR
* Misformatted data
* Text encoding artifacts
* Delimiter and offset issues
* Missing Data
* Null Values
* Unstructured data
* Partial or incomplete values
* Duplicates

## STEP 2 : REMOVING NON-PRINTING CHARACTORS
* I made use of the trim, clean, and substitute functions to get rid of these unwanted and non-printing characters.

## STEP 3: GET RID OF UNNECESSARY SPACING
* Removed unnecessary spacing and adhere to the uniform pattern of spacing

## STEP 4: CONVERT 'TEXT-NUMBERES' TO NUMBERS
* some numbers might be stored as text and this could be an issue

## STEP 5: CORRECT CASES IE UPPER AND LOWER CASES
* To ensure a professional and clean appearance Correct Use of CaseS

## STEP 6: PARSE DATA TO COLUMNS
* This is for data crammed into a single spreadsheet cell

## STEP 7: USE THE @CONCATENATE and @SPLIT fUNCTIONS TO RESTRUCTURE RECORDS to
* These two functions are super-handy if you have data that needs to be split or combined. @CONCATENATE will create a single column from multiple columns and values, you can even insert text in between the concatenated values

## STEP 8: GET RID OF DUPLICATES
