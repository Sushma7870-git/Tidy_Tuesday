# Black Population Density over the USA

## 📌 Project Overview

The overall goal of this project is to **explore and visualize the distribution and density of the Black population across U.S. states**. 

Through various interactive visualizations—including bar charts, choropleth maps, and bubble plots—this project aims to highlight:
- The **total size** of the Black population in each state
- The **density** of Black populations relative to total state populations
- The **geographic distribution** of Black populations across the United States

---

## 📊 Dataset Overview

This dataset captures detailed information about the Black population across U.S. states.

### 🗂️ Processed CSV Columns

| Column Name               | Description |
|---------------------------|-------------|
| `id`                      | Unique identifier for each U.S. state, corresponding to FIPS codes (Federal Information Processing Standards). Useful for mapping. |
| `state`                   | Full name of each U.S. state (e.g., "California", "Texas"). |
| `state abbreviation`      | Two-letter abbreviation for each state (e.g., "CA", "TX"). |
| `population`              | Estimated Black population, represented as a range (e.g., "10,000 - 50,000"). |
| `black population`        | Midpoint of the population range used for calculations and visualizations (e.g., midpoint of "10,000 - 50,000" is 30,000). |
| `State population`        | Total population of each state, used to calculate relative density. |
| `black_population_density`| Calculated field representing the ratio of the Black population to the total state population. Helps compare relative proportions across states. |
| `region`                  | U.S. states grouped into Census-defined regions (e.g., Northeast, Midwest, South, West). Useful for regional analysis. |

---

## 📈 Visualizations

### 1. Choropleth Map

The Choropleth Map in this project visualizes the **Black population density across U.S. states**, using color shading to represent the proportion of the Black population relative to the total state population.

- States are color-coded based on their calculated Black population density.
- A **blue color scale** is used:
  - **Darker shades** indicate higher Black population density.
  - **Lighter shades** represent lower density.
- **Hover interaction** reveals:
  - State name  
  - Black population density  
  - Total Black population  

This visualization helps highlight **geographic trends and regional disparities**, allowing users to easily identify states with larger or smaller shares of the Black population.

---

### 2. Bubble Plot

The Bubble Plot visualizes the **relationship between Black population density and total state population**.

- Each **bubble** represents a U.S. state.
- **Size** of the bubble: Total population of the state.
- **Color**: Represents the Black population density.
- **X-axis**: U.S. states (labeled).
- **Y-axis**: Black population density.
- **Color coding** reflects **U.S. region** (e.g., South, Northeast).

#### 💬 Tooltips show:
- State name  
- Total population  
- Black population  
- Density  
- Region  

#### 🔀 Interaction:
- A **region dropdown filter** allows users to isolate and view data for specific U.S. Census regions.

This visualization allows for an easy comparison of **population size vs. Black population density**, offering insight into:
- States with both high population and high Black population density  
- States with large populations but comparatively low density of Black residents  

---

## 🧭 Goals

- ✅ Visualize Black population size and density across states
- ✅ Create interactive visual tools for geographic and demographic analysis
- ✅ Identify regions with higher proportional representation of Black communities
- ✅ Facilitate public understanding of demographic distribution patterns

---

## 📚 Source

- **U.S. Census Bureau**, *Current Population Survey, Annual Social and Economic Supplement, 2023*

---

*Built with ❤️ for demographic insight and data storytelling.*
