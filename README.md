# Python data Web Scraping example
 The main goal of this project is to do a validation of a COVID-19 database, checking if the values are correct for each region.
 In order to do that, the code has four objectives: Web Scraping of a COVID-19 database, a pandas DataFrame conversion, data validation and an export to Excel file. 
 
1. Web Scrapping: with Selenium the code access the web page: https://worldometers.info/coronavirus/. Cookies elements must be accepted. 

![Webpage](https://user-images.githubusercontent.com/87708237/127035286-5972f207-899c-45c4-97d1-ce65bd57fbcd.JPG)
(COVID-19 DATABASE)

2. Pandas DataFrame conversion: for each region (Europe, North America, Asia, South America, Africa and Oceania) the code has to search the entire html until a table is found. This table is then converted through pandas extension.  

3. Data validation: the validation test is to verify if the sum of all the countries values of a region is the same as the total value of that region. 

![Validation criteria](https://user-images.githubusercontent.com/87708237/127041123-e84fbbc8-9a91-4a3d-8e17-d7bc8ffa1753.jpg)
(Validation test)

4. Export to Excel file: the code was written with google colab. The image below shows where the Excel file can be downloaded. 

![Export_to_Excel](https://user-images.githubusercontent.com/87708237/127042603-28a8ce7c-98cd-41ea-a492-216095b2c362.jpg)




