# Real Estate OSINT Phone Number Finder Tool

**Nicholas Nguyen**

---
 
 ## The objective of this project is to identify phone numbers of home owners from a CSV involving names & home addresses.
 

---

+ **Data** : `raw_housing_data.csv`` | `df3`
  + Source : Public Housing Data
  + Size : 3230 rows × 40 columns | 12,712 elements
  + Columns : `['first', 'middle', 'last', 'addy', 'addy_link'] `
 
  
| **Name**   | **Description** | **dtype** |
| ----------- | ----------- | ------- |
|`first`|_first name_| object |
|`middle`|_middle name_|object|
|`last`|_last name_|object|
|`addy`|_address_|object|
|`addy_link`|_address link_|object|

---

**Primary Findings**
+ Phone numbers are bolded out. ID's are connected to names. Use ID's for searching for people. Discord webhooks to output information.

**Recommendations**
+ Find faster way to run scraper tool.

**Conlusions**
+ Ran into lots of issues, but mainly best way to scrape is to identify id associated with person, assuming person's name is correctly stated on CSV. 

**Next Steps**
+ Utilize peoplelooker for more information! Off-load from .ipynb/Jupyter. Export data directly to SQL DB.

---

**In this Repository**
- `code` : this folder contains all notebooks associated with the project
  - `Cleanse_Data_and_Scrape_Nums.ipynb`

- `data` : this folder contains all csvs collected or created throughout the project
  - `raw_housing_data.csv`
  - `clean_data.csv`
