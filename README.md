# Automation_data_extractor

This Automation programs are to extract data from different platform by using selenium and beautifulsoup




Their programming may differ but they all flow similar pattern
1. User has to input product name 
2. add the product name into general link to get page number (didn't done it few as they have same page number)
3. then extract url of every products 
    i. generate every page url by adding product name and page number
    ii. than extracted the url of every products from every page
4. then, open the first product and extract all its features 
5. create a DataFrame with name,price and extracted features as columns and rows equal to number of extracted urls
6. then, open every product webpage with extracted urls and extract the data for dataframe
7. optional, in this we are extracting the features of first product only to get the every feature we see just de-comment the the certain code (code is commented in the file as every file has different code i can't point it here)
