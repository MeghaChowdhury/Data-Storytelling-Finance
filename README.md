# Data Storytelling in Finance

**Author:** Megha Chowdhury  
**Live App:** [Click here to view the Shiny app][(https://meghachowdhury.shinyapps.io/Data_storytelling_project_group_M/)]  

## 📌 Project Overview
This project explores the relationship between **infrastructure access** — specifically **electricity** and **internet availability** — and **education outcomes** across countries of different income levels. The analysis was conducted as part of the *Data Storytelling in Finance* course, with a focus on transforming raw data into an engaging, interactive narrative.

The project was implemented as an **interactive R Shiny dashboard**, allowing users to explore patterns, correlations, and comparisons between countries and income groups.

---

##  Dataset
The dataset comes from the **World Bank Open Data** repository and includes:
- **Electricity access (%)**
- **Internet users (%)**
- **GDP per capita (current US$)**
- **Education outcomes** (e.g., school enrollment rates, literacy rates)
- **Country income classifications**

Data covers multiple countries and years, enabling both **cross-country** and **time-series** comparisons.  
*Note: The full dataset is not included in this repository due to file size limitations, but it can be obtained directly from the [World Bank Data Portal](https://data.worldbank.org/).*

---

##  Main Findings
1. **Electricity access and education outcomes** are strongly correlated in lower-income countries, but the relationship flattens for high-income nations where access is already universal.
2. **Internet penetration** is a more significant predictor of improved education outcomes in middle-income countries than in low-income countries.
3. **High GDP per capita** does not guarantee the highest education outcomes — some upper-middle-income countries outperform high-income ones in specific metrics.
4. The interactive visualizations reveal clear **regional clusters** where infrastructure and education progress together.

---

##  Technical Details
- **Language:** R  
- **Framework:** R Markdown with `shiny` runtime  
- **UI Theme:** [`rmdformats::downcute`](https://github.com/juba/rmdformats)  
- **Visualization Libraries:** `ggplot2`, `plotly`, `reactable`, `ggtext`  
- **Deployment:** [shinyapps.io](https://shinyapps.io/)  

The interactive dashboard includes:
- **Heatmaps** for cross-country comparisons
- **Bar charts** for ranking countries by indicators
- **Multi-series charts** for comparing variables over time
- **Filter controls** for selecting years, regions, and income groups

---

## Repository Contents
- `Data_storytelling_project_group_M.Rmd` – main R Markdown source code for the dashboard  
- `Data_storytelling_project_group_M.html` – compiled static HTML output  
- `screenshots/` – images of the deployed app for quick preview  
- `LICENSE` – MIT license for reuse  
- *(Dataset not included due to size limits — see above for source)*

---

##  License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact
If you have questions, feel free to reach out via GitHub issues or [LinkedIn](https://www.linkedin.com/).

---

