# vest-fl-2016
Partner data validation for Florida, 2016. Data Partners: VEST. 

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-florida-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

### **Raw from source:**
- File: VEST Florida, 2016
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/IAELIN&version=54.0)
  - AWS: `fl_2016` (available upon request)
  - Accessed: March 17th, 2021

- File: VEST Florida, 2016 (Documentation)
  - Online: [Harvard Dataverse Link](https://dataverse.harvard.edu/file.xhtml?fileId=4441609&version=54.0)
  - AWS: `documentation.txt` (available upon request)
  - Accessed: March 17th, 2021

- File: Florida 2010 Census Blocks
  - Online: [Redistricting Data Hub Link](https://www.redistrictingdatahub.org/state/florida/)
  - AWS: `fl_2010_b_bound` (available upon request)
  - Accessed: March 24th, 2021

- File: Florida Precinct-level Election Results
  - Online: [Florida Division of Elections](https://dos.myflorida.com/elections/data-statistics/elections-data/precinct-level-election-results/)
  - AWS: `precinctlevelelectionresults2016gen` (available upon request)
  - Accessed: March 17th, 2021

- File: Florida Precinct Shapefiles
  - Online: n/a
  - AWS: `Precinct and Polling Place Files - 2012-present - last checked 7-23-2020` (available upon request)
  - Accessed: January 15th, 2021
  - Note: These files were accessed via a public records request with the Florida DOS. In a handful of cases, we loaded files and deleted columns or otherwise cleaned them to make the files easier to load.
 
### **File Processing:**
- VEST File: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/IAELIN&version=54.0
- Processing and Validation Steps: `VEST_FL_16_replication.ipynb`
- Notes / Methodology: Comments on `VEST_FL_16_replication.ipynb`
