# Nigeria-COVID-19-Data-Analysis-Using-Python

Data Scientist Microdegree Capstone Project

# Project Overview

This project investigates COVID-19’s stay in Nigeria; exploring its effects on the economy and health sector among others. The solution will also be stated.

# Project Steps

**Step 1**: The appropriate libraries were imported and data was scraped from the <a href = 'https://covid.ncdc.gov.ng'> Official NCDC Website </a> 

Libraries Imported

- requests
- numpy
- urllib.request
- pandas
- csv
- BeautifulSoup from bs4
- seaborn
- matplotlib.pyplot
- warnings
- time

Methods Used

- time()
- get()
- find()
- find_all()
- append()
- strip()
- reshape()
- read_html()

Attributes Used

- content

**Step 2**: Data was extracted from the Josh Hopkins Data Repository

Methods Used

- read_csv()

**Step 3**: Data was extracted from external data sources

Methods Used

- read_csv()

**Step 4**: Basic information about the datasets was viewed

Methods Used

- info()
- head()

**Step 5**: Columns from the NCDC data were renamed to more appropriate names and special characters were removed from the numerical columns. Data from Josh Hopkins Repository which contained global data were stripped to obtain Nigeria's data.

Methods Used

- rename()
- apply()
- drop()
- melt()
- to_datetime()

Attributes Used

- columns

**Step 6**: Analyses were performed on the data and visualizations were created.

Methods Used

- nlargest()
- color_palette()
- set_context()
- figure()
- title()
- xlabel & ylabel
- xticks & yticks
- diff()
- max()
- idmax()
- rename()
- replace()
- merge()
- twinx()
- corr()
- set_xticklabels & set_ylabel
- savefig()
- abs()
- plot_relation()
- sum()
- legend()
- xlim & ylim
- axhline()

Attributes Used

- index
- Date

Plots Created

- barplot
- lineplot
- pointplot
- regplot
- heatmap
- pie

Expressions

- lambda expression

# Presentation

Can be found in <a href = 'covidproject.pptx'> covidproject.pptx </a>
