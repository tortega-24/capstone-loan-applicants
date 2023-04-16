# Welcome to the Loan Application Project repository

  This document will provide a fairly comprehensive view of the project. Links to certain resources will be cited at the bottom and referenced using numbers. The project's data comes from A Kaggle dataset [1] describing loan application data from 2007-2018. The data, totaling close to 30 million rows, belongs to LendingClub. Founded in 2006, LendingClub is a financial technology company that offers a wide range of services to customers. LendingClub's loan service allows customers to submit loan applications and potentially connect with interested investors. This is called a peer-to-peer lending system.
  The Kaggle dataset contains accepted and rejected applicants that are split into two separate tables. The rejected applicant table has the vast majority of rows with approximately 27 million. The rejected applicant table has a total of 9 columns. The accepted applicant table has about 2 million rows and over 100 columns. A separate Kaggle resource [2] was used to provide a definition for each column. The data was downloaded into zip files and extracted using 7-Zip [3].
  Once the data was extracted from the zip file, each table was loaded into a Jupyter Notebook file to due some general pre-processing. This includes the selection of columns, handling missing values, and the matching of columns from both loan applicant tables. For a detailed look at the columns, please see the project proposal. At the end of the pre-processing steps, three tables were built: a table mixing 100,000 rows of accepted and rejected applicants, one table containing accepted applicant data, and another table containing ZIP Code data.
  




[1] Data Source: https://www.kaggle.com/datasets/wordsforthewise/lending-club?select=accepted_2007_to_2018Q4.csv.gz
[2] Data Dictionary: https://www.kaggle.com/datasets/jonchan2003/lending-club-data-dictionary?select=Lending+Club+Data+Dictionary+Approved.csv
[3] Extracting Data: https://www.7-zip.org/

Resources:
zip-codes
https://www.unitedstateszipcodes.org/
https://www.census.gov/cgi-bin/geo/shapefiles/index.php
site the data comes from
https://www.lendingclub.com/investing/peer-to-peer

good credit score (vantage and fico)
https://www.experian.com/blogs/ask-experian/credit-education/score-basics/what-is-a-good-credit-score/

harship plan 
https://www.creditkarma.com/credit-cards/i/how-hardship-plan-can-affect-credit#:~:text=A%20hardship%20plan%2C%20also%20known,right%20for%20your%20financial%20situation%3F
