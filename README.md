# Vélib' Métropole – Spatial Distribution Analysis

##  Objective

This project analyzes whether Vélib' bike-share stations in Paris are uniformly distributed or whether there are spatial differences between the city center and the periphery.

---

##  Methodology

The analysis follows a complete data science workflow:

- Data extraction from the Paris open data API
- Data cleaning and preprocessing
- Feature engineering (computing distance from the city center)
- Classification of stations into:
  - Central (≤ 5 km)
  - Peripheral (> 5 km)
- Statistical comparison of station capacities
- Data visualization (maps, bar charts, scatter plots, boxplots)
- Statistical testing using the Mann–Whitney U test

---

## Setup and Installation

Clone the repository:

```bash
git clone https://github.com/Amzilynn/The-Quantic-Factory-Test.git
cd The-Quantic-Factory-Test
   ```

2. **Install the required dependencies**:
   The notebook relies on a few Python libraries (like `pandas`, `requests`, `matplotlib`, `seaborn`, and `jupyter`). You can install them using the provided `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

##  Data Source
Paris Open Data: https://opendata.paris.fr/pages/home/


