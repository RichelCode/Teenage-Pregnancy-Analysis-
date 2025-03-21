# **Teenage Birth Rates in the U.S. (2003-2020) - Data Analysis**

## **Project Overview**
This project analyzes teenage birth rates in the United States at the county level from **2003 to 2020**. The goal is to uncover trends, regional disparities, and potential policy implications using **intensive exploratory data analysis (EDA) and advanced visualizations in R**.

## **Project Structure**
```
├── data/                   # Raw and processed datasets
├── scripts/                # R scripts for analysis and visualization
├── notebooks/              # R Markdown files for documentation and reporting
├── results/                # Figures, tables, and summary reports
├── README.md               # Project overview and setup instructions
└── report/                 # Final project report (R Markdown & PDF)
```

## **Key Analysis Steps**
### **1. Data Cleaning & Preparation**
- Handling missing values and inconsistencies.
- Transforming categorical and numerical variables.
- Preparing the dataset for visualization and modeling.

### **2. Exploratory Data Analysis (EDA)**
- National and state-level trends over time.
- County-wise distribution of teenage birth rates.
- Identification of high and low-rate regions.
- Statistical summaries and confidence interval analysis.

### **3. Advanced Visualization (ggplot2)**
- Heatmaps and choropleth maps for county-level insights.
- Time-series plots showing birth rate trends.
- Boxplots, violin plots, and density distributions.
- Bayesian credible interval analysis.

### **4. Statistical & Predictive Modeling (Optional)**
- Bayesian hierarchical models to estimate birth rates.
- Time-series forecasting to predict future trends.
- Model comparison and validation.

### **5. Key Findings & Insights**
- Summary of major findings from the analysis.
- Discussion of public health policies and interventions.

## **Setup Instructions**
### **Prerequisites**
- **R (version 4.x or higher)**
- R packages: `tidyverse`, `ggplot2`, `dplyr`, `sf`, `tmap`, `brms` (for Bayesian modeling, if needed)
- RStudio (recommended for R Markdown rendering)

### **How to Run the Project**
1. Clone the repository:
   ```sh
   git clone https://github.com/RichelCode/Teenage_Pregnancy_Analysis.git
   cd teen_birth_rates_analysis
   ```
2. Install required R packages (if not already installed):
   ```r
   install.packages(c("tidyverse", "ggplot2", "dplyr", "sf", "tmap"))
   ```
3. Open `notebooks/teen_birth_rates_analysis.Rmd` in RStudio.
4. Run the entire R Markdown file or execute step-by-step.
5. Check the `results/` folder for generated plots and reports.

## **Future Enhancements**
- Interactive dashboards using `shiny`.
- Machine learning models for prediction.
- Deeper statistical analysis of demographic and socioeconomic influences.

Work in Progress. Updates will be made as the project progresses. Stay tuned.

