# Assessment

## Approach to the Solution

1. Read the **Input.xlsx** file to extract the **URL** and **URL_ID**
2. Use the Pandas and Beautifulsoup library in python to exttract the HTML content from the web page
3. After extraction of the HTML content take the tags like <article>, <div, class = 'content'> and <div, class = 'post-content'> because generally the article's contetnt is put into these tags
4. After extracting the content from these tags store it in a file with name **{URL_ID}.txt** in the folder **file_output**
5. Iterate over all the tuples int the **Input.xlsx** and perform the same operation of extraction

6. When all the URLS' content have been extracted now task at had is to determine the variables mentioned in the assessment
7. Use the package **nltk** for the separation of words and lines in the file
8. Use the definitions and the libraries in python to determine the values of the variables and store it in the respective fields in the file **Output Data Structure.xlsx**
9. Iterate over all the files in the folder **file_output** and perform the analysis to store the data in the file **Output Data Structure.xlsx**

## Running the file

1. Clone the repository

`git clone https://github.com/tanmay233/blackcoffer_data_science/`

2. Install Dependencies

`pip install pandas requests beautifulsoup4 openpyxl`

`pip install pandas nltk openpyxl`

3. Run the pyton script

`python assessment.py`

