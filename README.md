# Data Storytelling in Finance

**Author:** Megha Chowdhury  
**Live App:** [View the deployed Shiny app](https://meghachowdhury.shinyapps.io/Data_storytelling_project_group_M/)

---

## 📌 Project Overview

This project explores the relationship between **infrastructure access** — specifically **electricity** and **internet availability** — and **education outcomes** across countries of different income levels.  
The analysis was conducted as part of the *Data Storytelling in Finance* course, with a focus on transforming raw data into a compelling data-driven narrative.

---

##  Dataset

The dataset comes from the **World Bank Open Data** repository and includes:

- **Electricity access (% of population)**
- **Internet users (% of population)**
- **GDP per capita (current US$)**
- **Education indicators** (e.g., secondary school completion, enrollment, literacy)
- **Country income classifications** (Low, Lower-Middle, Upper-Middle, High)

The data spans multiple years and countries, allowing for both **cross-country** and **time-series** comparisons.

> *Note: The full dataset is not included in this repository due to file size constraints, but it can be accessed via the [World Bank Data Portal](https://data.worldbank.org/).*

---

##  Main Findings

1. **Electricity access and education outcomes** are strongly correlated in lower-income countries, but the relationship flattens for high-income nations.
2. **Internet penetration** tends to be a more significant predictor of improved education outcomes in middle-income countries.
3. **High GDP per capita** does not automatically translate into better education outcomes — some upper-middle-income countries outperform high-income ones on key metrics.
4. **Regional clusters** show infrastructure and education often advance hand-in-hand, but disparities persist where investment is lacking.

---

##  Technical Details

- **Language:** R  
- **Framework:** R Markdown with `shiny` runtime  
- **UI Theme:** [`rmdformats::downcute`](https://github.com/juba/rmdformats)  
- **Libraries Used:** `ggplot2`, `plotly`, `reactable`, `ggtext`  
- **Deployment:** Hosted on [shinyapps.io](https://www.shinyapps.io/)

---

##  Repository Contents

- `Data_storytelling_project_group_M.Rmd` – R Markdown source code for the dashboard  
- `Data_storytelling_project_group_M.html` – Compiled static HTML output  
- `screenshots/` – Preview images of the app  
- `LICENSE` – MIT license for reuse  
- *(Dataset not included — see World Bank link above)*

---

##  License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

##  Contact

If you have any questions or feedback, feel free to reach out via GitHub Issues or [connect with me on LinkedIn](https://www.linkedin.com/).
