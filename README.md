## Group 7 Project 1
Key contributors are;
Bradley, Michelle, Priyanshu and Rhea

## Summary
In this repository, Australian ownership data of each vehicle type is assessed against the corresponding postcode to gain an understanding of current trends of each vehicle type. It then focuses on electric vehicles, investigating the geographic impact on the number of electric vehicle registration, and what a typical person's demographic is that owns an electric vehicle.

## Initial Steps
Group communication was through Slack channel group.
The initial repo on GitHub was created called ‘Project1_Group7’. 
The group settled on performing data analysis on Electric Vehicle ownership distribution within Australia. With the questions to be answered as;
1.What proportion of the Australian market is EV for the year 2023?
2.a. What is the trend for EV ownership for the 3 years up to 31 Jan 2023? 
2.b. How does EV ownership trend compare to ICE ownership trend?
3. What geographical location has the greatest ownership per capita?
4. What is the demographic for those that own EV?

## Data cleanup
The main data set used was of the geographic distribution of vehicle registrations, this dataset was checked using Excel. Two files were created from the dataset, an excel file and a .csv file both were uploaded to the Repo. 
The 2021 Census data sourced from the Australian Bureau of Statistics was cleaned using a Jupyter notebook. This included removing Nan values, renaming columns, converting strings to numeric and calculating median values.

## Repo cleanup
Two folders were created to hold the input data and the output data, these were called Resources and Output. Both the raw data and cleaned data sets were placed in the Resources folder. The raw data was cleaned within Jupyter notebook, and the cleaning can be seen in the ‘’Group 7 Data Cleanup’ notebook. The applicable content was then moved into the folders and the Jupyter notebooks updated with the new paths

## Data Analysis
A separate Jupyter notebook was created to contain our analysis code for  plotting, using the already cleaned data files. This is labelled ‘Group 7 Data Analysis’. 

## Installation and Running
For this code to run successfully, python is required to be installed along with the pandas tool library and either Jupyter lab or Jupyter notebook. One method to install these programs is to download Anaconda - link below. To run this code, open the file within Jupyter, ensure that the input files are directed correctly and run! Anaconda install: https://docs.anaconda.com/free/anaconda/install/

## Powerpoint creation
Powerpoint was created using Google docs, this was the original link before the final copy was uploaded to this Repo:
https://docs.google.com/presentation/d/1pTTtkyeSuwGjFQH9F93GtywNgc0CKskvL2CkmQppzqg/edit?usp=sharing

## Report Collaboration
Analysis & Conclusion was created using Google docs, this was the original link before the final copy was uploaded to this Repo:
https://docs.google.com/document/d/1_aKtNEHAW6sKacsjOwt3oplV4kXRflmD6ndCnzDiks4/edit?usp=sharing

## Rererences and Datasets
Australian Automobile Association of Australia - Electric Vehicle Index https://data.aaa.asn.au/ev-index/ - Free to use provided a link back to the original website is provided.
Australian Bureau of Statistics Census 2021 ‘G17 Total personal income (weekly) by age, by sex, Postal Areas (POA), https://explore.data.abs.gov.au/vis?tm=personal%20income&pg=0&df[ds]=C21_POA&df[id]=C21_G17_POA&df[ag]=ABS&df[vs]=1.0.0, accessed 04 January 2024 
Australian Postcodes a free and downloadable file of Australian Postcodes and their Lat, Lon https://www.matthewproctor.com/australian_postcodes - Free to use, donation to charity or contribution to dataset is encouraged.
Toyota. (n.d.). Toyota Hybrids. Retrieved from Toyota Australia: https://www.toyota.com.au/electrified/hybrid 
U.S. Department of Energy. (n.d.). Alternative Fuels Data Center: How Do All-Electric Cars Work? Retrieved from U.S. Department of Energy: Energy Efficiency & Renewable Energy: https://afdc.energy.gov/vehicles/how-do-all-electric-cars-work 

