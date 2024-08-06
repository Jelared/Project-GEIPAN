# GEIPAN Data Scraper

## About

A Python script for scraping data from the [GEIPAN](https://www.cnes-geipan.fr/) (Groupe d'Études et d'Informations sur les Phénomènes Aérospatiaux Non Identifiés). The script extracts information about UFO sightings, including the city, phenomenon, department, case classification, and observation date. The data is saved into a CSV file for further analysis.



## Features

* Data Extraction: Scrape data from multiple pages of the GEIPAN website.
* Data Processing: Organize the extracted data into a pandas DataFrame.
* CSV Export: Save the processed data into a CSV file.

## Technology

* Python 3.x
* BeautifulSoup
* Requests
* pandas
* tkinter (for file dialog)

## Install

1. Clone the Repository

```
git clone https://github.com/your-username/geipan-data-scraper.git
cd geipan-data-scraper
```

2. Install Dependencies

_Install the required Python libraries using pip_
```
pip install beautifulsoup4 requests pandas
```

3. Run the Script

_nsure you have the script GEIPAN_Data_Scraper.ipynb in your directory. Then run the Jupyter notebook or convert it to a Python script and run it_
```
jupyter notebook GEIPAN_Data_Scraper.ipynb
```
_or convert to Python script_
```
jupyter nbconvert --to script GEIPAN_Data_Scraper.ipynb
python GEIPAN_Data_Scraper.py
```

4. Export Data

_Follow the prompts to select the location to save the CSV file._

### **_Licence_**

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Jelared/Project-GEIPAN?tab=MIT-1-ov-file) file for details.

