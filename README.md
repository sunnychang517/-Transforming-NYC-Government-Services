# Transforming NYC Government Services with Text Classification

## Overview 
To use text classification to help NYC311 with service requests management by helping the call agents predict and redirect service requests to the right path for faster resolutions.

## Table of Contents:

[Overview](https://github.com/sunnychang517/-Transforming-NYC-Government-Services#overview)</br>
[Data Source](https://github.com/sunnychang517/-Transforming-NYC-Government-Services#data-source)</br>
[Access Data through SODA API](https://github.com/sunnychang517/-Transforming-NYC-Government-Services#access-data-through-soda-api-on-the-site)</br>
[Access Data by Clicking "View Data" on the site](https://github.com/sunnychang517/-Transforming-NYC-Government-Services#access-data-through-soda-api-on-the-site)</br>
[Tokenization](https://github.com/sunnychang517/-Transforming-NYC-Government-Services#tokenization)</br>
[Acknowledgement](https://github.com/sunnychang517/-Transforming-NYC-Government-Services#acknowledgement)

## Data Source
 NYC Open Data
 
 311. “311 Call Center Inquiry: NYC Open Data.” 311 Call Center Inquiry | NYC Open Data, 3 Apr. 2023, https://data.cityofnewyork.us/City-Government/311-Call-Center-Inquiry/wewp-mm3p. 
 
## Access Data through SODA API on the site

 1. Copy and Paste API Endpoint by clicking "API" which is next to "Export"
 2. Create a NYC Open Data account 
 3. Go to Edit Profile in order to modify developers settings
 4. Click and config Create New App Token on the Developer Settings tab
 5. Save App Token
 6. Open Python Environment
 7. Install sodapy package
 8. Run: 
 from sodapy import Socrata</br>
client = Socrata("data.cityofnewyork.us",</br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; app_token="*From the "App Token" column after you save the app token",</br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; username="*account username*",</br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; password="*account password*")</br>

## Access Data by Clicking "View Data" on the site

1. Clicking "View Data" on the site which will bring you to another webpage
2. Use the console to conduct filters, group, aggregate, or deselect columns 
3. Click "Export" when you are done with querying the data 

<strong>Note:</strong> If you want to use the API Endpoint when exporting then click [here](https://github.com/sunnychang517/-Transforming-NYC-Government-Services#access-data-through-soda-api-on-the-site)

## Tokenization
<h5>Same Labels in Training and Test Data Sets</h5>
<img width="250" alt="Screenshot 2023-05-01 004159" src="https://user-images.githubusercontent.com/54777897/236724636-26c77fec-dda6-4ca1-ad8f-6ba79750b86e.png">

## Acknowledgement: 
This is for a project at Columbia University where I learned how to improve my programming skills in python.</br>
Team member: Thomas Cooper</br>
Professor: John Oretga 
