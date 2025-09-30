# 🎮 Project 6 – Video Game Market Analysis (2000–2016)

**Objective**
Analyze historical video game sales data to understand market dynamics and inform future strategies by:
* Identifying platform lifecycles and the most promising platforms for future development.
* Determining the most lucrative genres based on total and average sales per game.
* Assessing the influence of critic and user ratings on commercial success.
* Mapping distinct consumer profiles across North America (NA), Europe (EU), and Japan (JP).

---

**Results**
* **Rating Correlation:** **Critic ratings** show a **stronger positive correlation** with sales than user ratings, indicating a higher commercial impact from professional reviews.
* **Platform Trends:** The average platform lifespan is **6 to 10 years**. Promising platforms include the **PS4, Xbox One, 3DS, and PC**, which show recent sales growth or stable, continuous revenue.
* **Lucrative Genres:** While **Action** and **Sports** lead in overall volume, **Shooter** and **Platform** genres are the most lucrative based on the highest average sales per game.
* **Regional Segmentation:** Consumer profiles are starkly divided:
    * **NA and EU** prioritize **home consoles** (Xbox 360, PS3) and **Action/Shooter** games.
    * **Japan** prefers **handheld platforms** (DS, PSP) and **Role-Playing Games (RPGs)/Adventure** titles.
* **Statistical Confirmation:** Two-Sample Independent T-Tests confirmed that the average user ratings are **significantly different** between:
    1.  **Xbox One and PC** platforms.
    2.  **Action and Sports** genres.

---

**Tools**
* **Python**
* **Pandas** (Data manipulation)
* **Matplotlib** & **Seaborn** (Data visualization)
* **SciPy** (Statistical analysis and hypothesis testing)

---

**Skills Learned**
* **Data Preprocessing and Cleaning** (Type conversion, handling `NaN` and 'tbd' values).
* **Exploratory Data Analysis (EDA)** (Trend mapping, Boxplots, Correlation analysis).
* **Feature Engineering** (Calculating `total_sales`).
* **Regional Market Segmentation** (Creating platform and genre profiles by region).
* **Hypothesis Testing** (Two-Sample Independent T-Tests for comparing means).

---

**Improvements / Future Work**
* Apply **predictive models** (e.g., Regression, Time Series) to forecast sales for the next year (2017).
* Conduct deeper analysis into the impact of **ESRB/CERO/PEGI ratings** on sales velocity across regions.
* Analyze sales revenue using the **most relevant period (2000–2016)** to avoid bias from old or underrepresented data.
