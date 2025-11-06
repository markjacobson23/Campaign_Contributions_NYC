[README.md](https://github.com/user-attachments/files/23402384/README.md)
# NYC Campaign Finance Analysis

## Overview

This project explores New York City campaign finance data using Python and Tableau. The goal is to extract meaningful insights from over 1.4 million contribution records spanning multiple election cycles, then show those insights visually. This work was conducted as a showcase of technical and analytical skills for a data analytics role.

---

## Dataset

* **Source**: NYC Open Data
* **Rows**: ~1.4 million (reduced to ~600,000 after cleaning)
* **Fields**: 54 original columns to 16 cleaned and engineered features used
* The raw CSV file is not tracked in Git due to size.
You can download it here: [data](https://catalog.data.gov/dataset/2021-campaign-contributions)

### Key Columns Used

* `AMNT`, `MATCHAMNT`, `PREVAMNT`: Monetary donation values
* `DATE`, `ELECTION`, `YEAR`, `MONTH`: Temporal tracking
* `STATE`, `CITY`, `ZIP`: Donor geography
* `C_CODE`, `OCCUPATION`, `EMPNAME`: Donor classification
* `RECIPNAME`, `OFFICECD`, `CANCLASS`: Candidate and campaign attributes

---

## Tools

* **Python and Pandas**: Data wrangling, cleansing, and exploratory analysis
* **Matplotlib and Seaborn**: Charting donation trends, distributions, and category breakdowns
* **Tableau**: dashboards and geospatial visualizations

---

## Key Insights

* **Donation Surges in Election Years**: Clear spikes every 4 years in volume and count
* **Local Dominance**: NY donors contribute the most by far geographically and financially
* **Donor Profile**: Most contributions are modest (under $250), with rare multimillion dollar outliers
* **Donor Type**: Individuals dominate, but organizations like corporations and unions also play a role
* **Occupation & Employer Trends**: Public sector jobs, lawyers, and teachers appear frequently among top contributors
* **Payment Methods**: Check and credit card dominate

---

## Tableau Dashboards

Dashboards were created to visualize:

* Time trends (volume, count, median donation)
* Geographic breakdowns
* Log-scaled donation distributions

**Access Link**: [Public Tableau Dashboard](https://us-east-1.online.tableau.com/#/site/markjacobson23-a85a706a5d/workbooks/3568585?:origin=card_share_link)

---

## Project Structure

Campaign_Contributions_NYC/
├── data/
│   ├── Campaign_Contributions.csv        # Raw donation dataset
│   └── Cleaned_Donor_Data.csv            # Cleaned and preprocessed dataset
├── python_notebooks/
│   ├── DataClean.ipynb                   # Notebook for data cleaning and preparation
│   └── GeneralAnalysis.ipynb             # Main exploratory analysis and visualizations
├── tableau_dashboards/
│   ├── Donation Distribution Insight Dashboard.pdf 
│   ├── Geographic Insight Dashboard.pdf
│   └── Time Insight Dashboard.pdf

---

## future additions

* Implement SQL-based transformations or DBT integration
* Explore predictive modeling: donor likelihood, fraud detection, etc.
* Create companion slide deck or web story for broader audiences

---

## Author

Mark Jacobson | [LinkedIn](https://www.linkedin.com/in/markjacobson23)

---

## Tags

`Python` `Pandas` `Data Analysis` `Campaign Finance` `Tableau` `NYC` `Data Visualization` `EDA`
