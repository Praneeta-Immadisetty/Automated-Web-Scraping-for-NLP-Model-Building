# Automated-Web-Scraping-for-NLP-Model-Building
This model extracts weblinks from an excel sheet and scrapes all the text from the webpage and stores it as separate sentences. Can be used for dataset creation for NLP model building.

Here the sample excel sheet is "RVCE_Text data search_Telugu - AGRICULTURE.csv".
The extracted text is organised as follows:

      .
      ├── Extracted_Sample        
      │   ├── Topic1            #folder named after topic title from excel sheet   
      |   |   ├── TextLink1     #extracted text file corresponding to the web page link
      |   |   ├── TextLink2
      |   |   └── ...
      │   ├── Topic2          
      |   |   ├── TextLink1    
      |   |   ├── TextLink2
      |   |   └── ...
      └── ...

The code can be customized according to the excel formatting.
