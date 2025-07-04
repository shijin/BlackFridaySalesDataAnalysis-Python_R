# Black Friday Sales Data Analysis

An end-to-end Exploratory Data Analysis project using Python and R

## Objective

* To analyze customer purchase patterns during the Black Friday sales event and generate business insights for marketing and product optimization.

## Dataset Overview

* Source: Kaggle

* Size: 537,577 rows × 12 columns

* Features: Demographics (age, gender, occupation, marital status), City category, Product IDs, Purchase amount

## Tools & Technologies

* Python: pandas, seaborn, matplotlib

* R: dplyr, ggplot2

* Platforms: Jupyter Notebook, RStudio, RPubs

## Key Insights

* Age group 26–35 had the highest purchase volume and spending

* Product Category 1 was the most frequently purchased

* Occupations 12–16 showed wider purchase variation and higher median spend

* Significant relationship between gender and product category (Chi-square test)

## Business Recommendations

* Target males aged 26–35 with relevant ads

* Prioritize offers for Product Category 1

* Focus urban campaigns in City Category B

* Consider tailored upsell strategies for high-spend occupations

## Deliverables

* BlackFridaySales-ExploratoryDataAnalysis.ipynb (Python notebook)

* R Report on RPubs: [View Report](http://rpubs.com/shijinramesh/blackfridaysales)

* Project Report (PDF)

* Scope of Work (PDF)

* requirements.txt

### Running the Notebook

- This project was built using Jupyter Notebook and is compatible with Google Colab.

### To Run on Google Colab:
1. Open this notebook in Colab:  
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/shijin/BlackFridaySalesDataAnalysis-Python_R/blob/main/BlackFridaySales-ExploratoryDataAnalysis.ipynb)

2. Upload the dataset manually:  
   - Click the file icon (left sidebar in Colab)
   - Click **Upload**, then select `BlackFriday.csv`  
   *(or run the cell `from google.colab import files` to upload interactively)*

3. Alternatively, replace the `read_csv()` line with a GitHub raw link:
```python
df = pd.read_csv('https://github.com/shijin/BlackFridaySalesDataAnalysis-Python_R/blob/main/BlackFriday.csv')
```
## Author

* Shijin Ramesh | Data Analyst 
