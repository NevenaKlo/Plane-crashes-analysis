# **Airplane Crash Analysis (1919–2023) · IASS – International Alliance for Safe Skies**

This repository contains an exploratory and statistical analysis of nearly **25,000** airplane crashes that occurred between **1919** and **2023**.  
The project, commissioned by the newly founded **IASS (International Alliance for Safe Skies)**, aims to identify patterns, trends, and insights that can help improve flight safety, using both statistical summaries and visualizations.

---

## **📦 Dataset**

Each row in the dataset represents a crash and contains the following fields:

- **`date`** — date of the crash  
- **`type`** — aircraft type/model  
- **`registration`** — aircraft registration code  
- **`operator`** — airline or operator  
- **`fatalities`** — number of fatalities (may contain non-standard formats such as `"n + n"` or `"unknown"`)  
- **`location`** — crash location  
- **`country`** — country where the crash occurred  
- **`cat`** — crash category (as classified by ASN)

**Data quality note:**  
The dataset contains missing values and heterogeneous formats (e.g., dates as strings, textual fatalities). Cleaning and normalization steps are included in the project.

---


## **📊 Example Insights Produced**

- **Most common country** for crashes (by mode of the `country` column).  
- **Day-of-week analysis** to determine if crashes are more frequent on certain days.  
- **Suspicious date filtering** to avoid skewing results in time-based analysis.  
- **Safest operators** — operators with ≥10 crashes ranked by fatalities per crash.  
- **Post–9/11 impact** — comparison of crash counts and fatalities in the USA before and after September 11, 2001.

---

## **📈 Visualizations Created**

- **Bar charts** showing crash counts by country.  
- **Time series plots** showing crash trends over time.


## **Notes**

- The analysis is exploratory and depends on the quality and consistency of the provided dataset.  
- Missing and inconsistent data (e.g., in `fatalities` or `date`) were cleaned but may still affect interpretations.  
- Some bulk-entry days were excluded to avoid skewed results. 
