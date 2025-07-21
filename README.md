# ANALYSING HOUSING VIOLATIONS IN NEW YORK CITY

## Instructions for use

Before attempting to run any code please unzip the data file such that it will be accessible to the programs.

## Rubric Questions

#### What do I want to do?

We want to compare New York housing violations before covid (2019), after covid (2021), and current (2024)

#### Identify the data

We are using NYC Housing Preservation & Development open data API

#### What data is available to me?

Violation type, status, and location (Each row in this dataset contains discrete information about one violation of the New York City Housing Maintenance Code or New York State Multiple Dwelling Law. Each violation is identified using a unique Violation ID. These Laws are in place to provide requirements for the maintenance of residential dwelling units within New York City)

#### Where does the data come from? 

Violations against conditions, in rental dwelling units and buildings, that have been verified to violate the New York City   Housing Maintenance Code (HMC) or the New York State Multiple Dwelling Law (MDL)

#### Do I have consent to have it obtained?

YES 

(Public data sets made available on the web portal are provided for informational purposes. The City of New York does not warranty the completeness, accuracy, content or fitness for any particular purpose or use of any public data set made available on the web portal, nor are any such warranties to be implied or inferred with respect to the public data sets furnished therein.)
  
#### What am I going to do with this data?

We plan to visually compare data that can answer some or all of these initial questions: a spatial comparison of violations in the city, compare pre and post Covid conditions, identify areas that have violation anomalies, identify which violations are most common, what type of building structures have the most violations, and current status metrics.

#### Who is going to see it? 

This project will be completed for our INFO2201 Class for Prof. Laurie Jones.

#### What is my goal with sharing and using this data? 

Our goal is to complete an intersecting project that will provide practice for new coding skills.

#### What will I gain from it? 

New skills and a greater understanding of housing systems in New York City.

#### Will it affect the people whose data this is?

It could if we published our conclusions but our project is not ethically compromised as we have eliminated personal address data 
  
#### Whose data is it? 
Data provided by the Department of Housing Preservation and Development (HPD)

#### Do they know I am working with their data? 

It is open source data pinged through an approved API.

#### Have I communicated to the people whose data it is? 

No
  
#### Will you be able to identify people through this data? 

Individual address information was removed in our cleaning process and documentation is anonymized. 

#### Who will have access to the anonymized data? 

It is accessible to anyone who can access the website.

#### How will I anonymize the data? 

By removing identifying factors.

#### What are your KPIs (how would you define success)? 

Working together as partners to be present and keep up with daily/weekly class expectations.

Gaining valuable insight in the recent changes in NYC housing violations.

##### Are they possible? 

Absolutely.

##### Are they aligned with protection and transparency? 

YES

#### How will you measure success? 

By overcoming coding obstacles through Google, class notes, and instructor help.
  
#### What will your process be? 

To complete each weekly task, which will progress our project naturally
  
#### What will your outcome be through working with this data? 

To complete a valid data collection that we can comprise to create visual comparisons of attribute features

## Journal

#### WEEK 4 DAY 4 
- worked as partners to identify our project
- created our GitHub project repository
- found our data
- each pulled the data and commited a working file to our joint repository
- [NYC Housing Preservation & Development]
- https://www.nyc.gov/site/hpd/about/open-data.page
- [Housing and Development (Housing Maintenance Code Violations)]
  

#### WEEK 5 DAY 4
- CLEAN AND SAVE DATA
- we looked at our NY housing violations data to identify which columns we would/might need for our project
- we identified which years we are going to use for our comparisons (2019[pre Covid], 2021[post Covid], 2024[current])
- within the NYC Housing Preservation & Development website dataset we downloaded our cleaned/selected data
- our cleaning excluded 30 columns of data including the columns that were unethical to use for our project. These columns included detailed address information which were not pertinant to our project. They also included data that was not necessary for our comparison.
- our cleaning identified 10 columns that could be useful information such as violation types (id #), building id (what type of building), borough and borough id    (where the violations occured in the city), the approve date, the class (seriousness of the violation), current status.
- we downloaded each seperate year and put them into a data file.
- the file was too big for GitHub our solution was to compress the file then push the compressed file to GitHub so that we could both access it for coding (this worked). This data must be uncompressed within our code for use.  
