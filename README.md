# Data Storytelling in Finance

**Author:** Megha Chowdhury  
**Live App:** [View the deployed Shiny app](https://meghachowdhury.shinyapps.io/Data_storytelling_project_group_M/)

---

##  Project Overview

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

### 🔍 Main Findings

---

#### 1.  Extreme Inequality in Education Access

- Top countries (e.g., Italy, Norway) have **~100%** secondary school completion.  
- Bottom countries (e.g., Chad, Niger) fall below **20%**.  
- This isn’t just about schools — it's about systemic inequality.

---

#### 2.  Infrastructure Drives Education Outcomes

- **High education countries** → **96% electricity**, **57% internet**.  
- **Low education countries** → **46% electricity**, **14% internet**.  
> Infrastructure is not optional — it's foundational.

---

#### 3.  Education, GDP & Internet Form a Vicious Cycle

- Low GDP + low internet = low education rates.  
- Wealthier, connected countries consistently perform better.  
- Breaking this cycle requires investment beyond schools.

---

#### 4.  Missing Data = Missing Voices

- Many **low-income nations** are **underrepresented** in global datasets.  
> Data gaps make inequality **invisible** to policymakers.

---

#### 5.  Infrastructure Before Policy

- Without electricity or internet, education policy alone won’t work.  
- Investment must first target **basic infrastructure**.

---

#### 6.  Progress Post-2015, Then a Setback

- **SDG efforts** boosted education after 2016 — peaking in **2020–21**.  
- **COVID-19**, economic shocks, and conflict drove a decline by 2023.  
> The data shows how fragile progress can be — and how urgent resilience is.

---

###  TL;DR: Funding infrastructure = funding education.


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
