# Welcome to the Loan Application Project repository

&nbsp;&nbsp;&nbsp;&nbsp;This document will provide a fairly comprehensive view of the project. Links to certain resources will be cited at the bottom and referenced using numbers. The project's data comes from A Kaggle dataset [1] describing loan application data from 2007-2018. The data, totaling close to 30 million rows, belongs to LendingClub. Founded in 2006, LendingClub is a financial technology company that offers a wide range of services to customers. LendingClub's loan service allows customers to submit loan applications and potentially connect with interested investors. This is called a peer-to-peer lending system.

&nbsp;&nbsp;&nbsp;&nbsp;The Kaggle dataset contains accepted and rejected applicants that are split into two separate tables. The rejected applicant table has the vast majority of rows with approximately 27 million. The rejected applicant table has a total of 9 columns. The accepted applicant table has about 2 million rows and over 100 columns. A separate Kaggle resource [2] was used to provide a definition for each column. The data was downloaded into zip files and extracted using 7-Zip [3].

&nbsp;&nbsp;&nbsp;&nbsp;Once the data was extracted from the zip file, each table was loaded into a Jupyter Notebook file to due some general pre-processing. This includes the selection of columns, handling missing values, and the matching of columns from both loan applicant tables. For a detailed look at the columns, please see the project proposal. At the end of the pre-processing steps, three tables were built: a table mixing 100,000 rows of accepted and rejected applicants, one table containing accepted applicant data, and another table containing ZIP Code data for all applicants.

&nbsp;&nbsp;&nbsp;&nbsp;Seven questions were proposed based on looking through the data. These questions were answered with a mix of graphical and tabular results. To solve some of these questions, outside resources were required to provide data and background knowledge. A great example of this is the use of U.S. Census geospatial data [4]. The geospatial data was used with loan applicant's ZIP Code data to build a map showing the ratio of accepted loan applicants across mainland states. Another resource comes from Experian and describes the range of FICO and Vantage scores [5]. The 'hardship' column was defined using a website by Credit Karma [6].
  


### Resources

[1] Data Source: https://www.kaggle.com/datasets/wordsforthewise/lending-club?select=accepted_2007_to_2018Q4.csv.gz

[2] Data Dictionary: https://www.kaggle.com/datasets/jonchan2003/lending-club-data-dictionary?select=Lending+Club+Data+Dictionary+Approved.csv

[3] Extracting Data: https://www.7-zip.org/

[4] U.S. Geospatial Data: https://www.census.gov/cgi-bin/geo/shapefiles/index.php

[5] FICO/Vantage Score: https://www.experian.com/blogs/ask-experian/credit-education/score-basics/what-is-a-good-credit-score/

[6] Hardship: https://www.creditkarma.com/credit-cards/i/how-hardship-plan-can-affect-credit#:~:text=A%20hardship%20plan%2C%20also%20known,right%20for%20your%20financial%20situation%3F

Extra Resources:

ZIP Codes: https://www.unitedstateszipcodes.org/
