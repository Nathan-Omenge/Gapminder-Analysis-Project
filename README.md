# Gapminder-Analysis-Project
This project demonstrates how to group, summarize, and visualize data using the `gapminder` dataset in R. It highlights the power of the `dplyr` package for data manipulation and the `ggplot2` package for creating insightful visualizations.
---

## 📂 Files in This Repository:
- **C3 Grouping Summarizing.Rmd**: R Markdown file containing the code and explanations for data aggregation and visualization tasks.

---

## 💻 Key Topics Covered:
### 1. **Summarizing Data**
- Use the `summarize()` function to calculate:
  - Median GDP per capita.
  - Median life expectancy.
  - Maximum GDP per capita.

### 2. **Grouping Data**
- Use `group_by()` to aggregate data by:
  - Year.
  - Continent.
  - Both year and continent.

### 3. **Visualization with ggplot2**
- Create scatter plots to visualize:
  - Changes in median life expectancy over time.
  - Median GDP per capita by continent and year.
  - Comparison of median GDP and life expectancy by continent in 2007.

---

## 🛠️ Libraries Used:
- **dplyr**: For data manipulation and aggregation.
- **ggplot2**: For creating visualizations.
- **gapminder**: Dataset used for the analysis.

---

## 📊 Visualizations:
1. **Median Life Expectancy Over Time**:
   - Scatter plot showing changes in life expectancy over years.

2. **Median GDP by Continent and Year**:
   - Colored scatter plot comparing GDP across continents over time.

3. **GDP vs. Life Expectancy (2007)**:
   - Scatter plot comparing median GDP and life expectancy for each continent in 2007.

---

## 🚀 How to Run:
1. Open `C3 Grouping Summarizing.Rmd` in RStudio.
2. Install the required libraries if not already installed:
   ```R
   install.packages(c("dplyr", "ggplot2", "gapminder"))
