# Boat Sales
This is a project for my data analyst course of CareerFoundry.

I serve as a data analyst for a website specializing in the sale of yachts and boats. 
The marketing team is currently crafting a weekly newsletter targeted at boat owners. 
The primary goal of this newsletter is to assist sellers in maximizing visibility for 
their boats and staying informed about prevailing market trends.

Story board with the main findings on this link:
https://public.tableau.com/views/6_7BoatSalesStory/Story1?:language=en-US&:display_count=n&:origin=viz_share_link
This storyboard doesn't contain every step I took as part of the analysis
only thode relevant to the final results

This data set is about the sales data of boats.
## 01.	Data Source
This data set is from the Kaggle.com website. 
https://www.kaggle.com/datasets/karthikbhandary2/boat-sales/data
Kaggle, operating under Google LLC, serves as a platform and online community for data scientists and machine learning practitioners. It facilitates users in discovering and sharing datasets, creating models within a web-based data science environment, collaborating with fellow professionals, and participating in competitions aimed at addressing data science challenges.
This data set is all about the popularity of the boats. It has 10 columns. It has details of the boats regarding the year it was built the type of boat, price and much more.

Source of geological data:
https://geojson-maps.ash.ms/

Source of data of tine series:
data = nasdaqdatalink.get_table('QDL/ODA', indicator='DEU_NID_NGDP')
https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data?select=DailyDelhiClimateTest.csv

## 02. Columns:
Price
Character, boat price listed in different currencies (e.g. EUR, Â£, CHF etc.) on the website
Boat Type
Character, type of the boat
Manufacturer
Character, manufacturer of the boat
Type
Character, condition of the boat and engine type(e.g. Diesel, Unleaded, etc.)
Year Built
Numeric, year of the boat built
Length
Numeric, length in meter of the boat
Width
Numeric, width in meter of the boat
Material
Character, material of the boat (e.g. GRP, PVC, etc.)
Location
Character, location of the boat is listed
Number of views last 7 days
Numeric, number of the views of the list last 7 days

## 03. LIMITATIONS:
1. Data Source Reliability:
   - The dataset is obtained from Kaggle, a platform for data scientists. While Kaggle is reputable, there might be variations in data quality based on individual contributors. No Warranty: CC0: Public Domain license includes a disclaimer stating that the work is provided "as is" without any warranties, which means the creator does not provide any guarantees or assurances regarding the quality or fitness for a particular purpose of the work.
2. Data Cleaning Decisions:
   - The decision to delete rows with missing values might lead to a loss of potentially valuable information.

## 04. ETHICAL CONSIDERATIONS:
1. Privacy Concerns:
   - The dataset involves information about boats and their characteristics. While it may not contain personal information directly, sharing similar datasets with more sensitive data could pose privacy concerns. 
2. Data Ownership and Attribution:
   - The Kaggle dataset has CC0: Public Domain licence. This means that the work is placed in the public domain, and anyone can use, modify, distribute, or otherwise utilize the work for any purpose, without any restrictions or requirements. The creator explicitly states that they have waived all copyright and related rights, effectively placing the work in the public domain. No Restrictions: Users can copy, modify, distribute, and perform the work, even for commercial purposes, without seeking permission from or providing attribution to the original creator. Global Applicability: The CC0 license is intended to be effective worldwide, to the extent permitted by law.


