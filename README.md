# NYC Housing Enforcement Analysis

## Geographic Patterns of Housing Complaints and Violations in New York City

A comprehensive data analysis examining housing maintenance code complaints and violations across NYC's 59 community districts during Spring-Summer 2024, revealing significant geographic disparities in housing quality and enforcement patterns.

### 🔍 Project Overview

This project analyzes 300,348 housing complaints and 447,154 violations from NYC Open Data to identify:
- Geographic concentration of housing issues
- Per capita complaint and violation rates by community district
- Temporal patterns and seasonal enforcement trends
- Correlation between complaints and violations (R² = 0.925)
- Policy recommendations for targeted interventions

### 📊 Key Findings

- **The Bronx Housing Crisis**: 4 of top 5 violation districts are in the Bronx, with rates 2x citywide average
- **Brooklyn's Enforcement Paradox**: Highest enforcement ratio (1.73 violations per complaint)
- **Geographic Inequality**: Gini coefficients of 0.438 (complaints) and 0.424 (violations)
- **Seasonal Spike**: June 2024 saw 130,000+ violations (2.1x normal monthly rate)
- **Hazardous Conditions**: 58.5% of violations are Class B or C (hazardous/immediately hazardous)

### 🛠️ Technical Stack

- **Languages**: Python 3.11
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Geospatial**: GeoPandas (choropleth mapping)
- **Statistical Methods**: Gini coefficients, Pearson correlation, linear regression

### 📁 Repository Contents
```
├── notebooks/
│   └── NYC_Housing_Analysis.ipynb          # Complete analysis workflow
├── data/
│   ├── cleaned_population.csv              # Population data by CD
│   └── data_sources.md                     # NYC Open Data links
├── outputs/
│   ├── figures/                            # 15+ publication-quality visualizations
│   ├── Furman_Housing_Analysis_Report.docx # Comprehensive report (20+ pages)
│   └── Housing_Analysis_Presentation.pptx  # Executive presentation (10 slides)
├── src/
│   ├── data_cleaning.py                    # Validation & standardization
│   └── visualization.py                    # Custom plotting functions
└── README.md
```

### 🔬 Methodology

1. **Data Collection**: Filtered 10M+ records to 750K Spring/Summer 2024 entries via NYC Open Data
2. **Data Cleaning**: Validated community district codes, removing <2% invalid entries (e.g., Brooklyn 86, Queens 26)
3. **Per Capita Analysis**: Normalized by 2020 Census population (per 1,000 residents)
4. **Geospatial Analysis**: Mapped patterns across 59 community districts
5. **Temporal Analysis**: Examined monthly trends and seasonal patterns
6. **Statistical Analysis**: Calculated Gini coefficients, correlation matrices, enforcement ratios

### 📈 Visualizations

The analysis includes 15 publication-quality figures:
- Per capita heat maps by community district
- Temporal trend analysis (complaints & violations)
- Violation class distribution (A/B/C severity)
- Geographic choropleth maps
- Borough-level comparison dashboards
- Lorenz curves for concentration analysis
- Correlation scatter plots with regression lines

### 🎯 Policy Recommendations

1. **Targeted Bronx Intervention**: Comprehensive housing preservation initiative for Districts 4, 5, 6, 7
2. **Brooklyn Best Practices**: Study high enforcement ratio protocols for citywide application
3. **Proactive Seasonal Inspections**: Formalize June inspection campaigns year-round
4. **Priority Hazardous Response**: Rapid-response protocols for Class B/C violations
5. **Tenant Support Programs**: Expand education in high-complaint districts

### 📄 Deliverables

- **Technical Report**: 20+ page analysis with methodology, findings, and recommendations
- **Executive Presentation**: 10-slide deck for stakeholder communication
- **Jupyter Notebook**: Fully reproducible analysis with 20+ code cells
- **Data Visualizations**: 15 professional figures (300 DPI PNG format)

### 🏆 Project Context

Prepared for NYU Furman Center Technical Assessment - demonstrating data analysis, geospatial analytics, and policy research capabilities for urban housing research.

### 📊 Impact

This analysis reveals that housing quality issues in NYC are not uniformly distributed, with the Bronx experiencing a concentrated housing crisis requiring urgent policy attention. The strong correlation between complaints and violations (R² = 0.925) validates the enforcement system's responsiveness while highlighting persistent geographic inequalities.

### 🔗 Data Sources

- [NYC Housing Maintenance Code Complaints](https://data.cityofnewyork.us/Housing-Development/Housing-Maintenance-Code-Complaints-and-Problems/ygpa-z7cr)
- [NYC Housing Maintenance Code Violations](https://data.cityofnewyork.us/Housing-Development/Housing-Maintenance-Code-Violations/wvxf-dwi5)
- [NYC Community District Shapefiles](https://www.nyc.gov/content/planning/pages/resources/datasets/community-districts)
- [Census Demographics](https://data.cityofnewyork.us/City-Government/Census-Demographics-at-the-NYC-Community-District-/5unr-w4sc)

### 📝 Skills Demonstrated

- Large-scale data processing (750K+ records)
- Data validation and quality assurance
- Geospatial analysis and choropleth mapping
- Statistical analysis (Gini coefficients, correlation)
- Data visualization and storytelling
- Policy research and recommendation development
- Technical documentation and reporting

### 📧 Contact

[Your Name] | [Your Email] | [LinkedIn]

---

**License**: MIT (or specify your preferred license)
**Date**: December 2024
```

---

## **💼 RESUME VERSIONS:**

### **Version 1: Technical Focus (Data Analyst/Data Scientist roles)**
```
NYC Housing Enforcement Analysis | Python, GeoPandas, Statistical Analysis
- Analyzed 750K+ housing complaints and violations across 59 NYC community districts to identify 
  geographic disparities in housing quality and enforcement patterns
- Performed data cleaning and validation on 10M+ records, implementing quality controls that 
  identified and removed <2% invalid entries through systematic validation logic
- Developed 15+ publication-quality visualizations using Matplotlib/Seaborn including choropleth 
  maps, heat maps, and correlation analyses revealing R² = 0.925 between complaints and violations
- Calculated Gini coefficients (0.438, 0.424) to quantify geographic concentration and identify 
  priority districts where rates exceed citywide averages by 2-2.6x
- Delivered comprehensive 20-page policy report and executive presentation to NYU Furman Center, 
  providing 5 targeted recommendations for housing preservation initiatives
```

### **Version 2: Policy/Research Focus (Urban Planning/Policy Analyst roles)**
```
Geographic Analysis of NYC Housing Quality & Enforcement | NYU Furman Center Assessment
- Conducted comprehensive analysis of 300,348 housing complaints and 447,154 violations to assess 
  housing conditions and enforcement patterns across NYC's 59 community districts
- Identified critical housing crisis in Bronx districts (4 of top 5 by violations per capita) with 
  rates 2x citywide average, informing targeted policy intervention strategies
- Discovered 58.5% of violations involve hazardous conditions (Class B/C), highlighting urgent 
  health and safety concerns requiring rapid-response protocols
- Revealed geographic inequality through Gini coefficient analysis and documented seasonal 
  enforcement patterns (June spike: 130,000+ violations, 2.1x normal rate)
- Synthesized findings into actionable policy recommendations including targeted Bronx preservation 
  initiatives, proactive inspection campaigns, and tenant education programs
```

### **Version 3: Balanced Technical + Impact (General roles)**
```
NYC Housing Quality Analysis | Python, Geospatial Analytics, Policy Research
- Analyzed 750K+ NYC Open Data records to identify housing complaint and violation patterns across 
  59 community districts, revealing significant geographic disparities requiring policy intervention
- Implemented data validation pipeline processing 10M+ records, standardizing district codes and 
  removing invalid entries to ensure analysis accuracy
- Created 15 publication-quality visualizations (choropleth maps, heat maps, time series) and 
  statistical analyses demonstrating strong correlation (R² = 0.925) between complaints and violations
- Identified Bronx housing crisis with violation rates 2-2.6x citywide average and 58.5% of 
  violations classified as hazardous, informing 5 policy recommendations for targeted interventions
- Delivered comprehensive technical report, Jupyter notebook, and executive presentation to 
  NYU Furman Center demonstrating data analysis and policy communication capabilities
```

### **Version 4: Concise (For resume with space constraints)**
```
NYC Housing Enforcement Analysis | Python, GeoPandas, Statistical Analysis
- Analyzed 750K+ housing records across 59 NYC community districts, identifying geographic 
  disparities where Bronx violation rates exceed citywide average by 2-2.6x
- Developed 15 publication-quality visualizations and calculated Gini coefficients (0.438, 0.424) 
  to quantify housing inequality and inform policy recommendations
- Delivered technical report and presentation to NYU Furman Center with 5 actionable policy 
  recommendations for targeted housing preservation initiatives
```

---

## **🏷️ GITHUB TOPICS/TAGS:**

Add these tags to your GitHub repository for better discoverability:
```
data-analysis
geospatial-analysis
python
pandas
geopandas
matplotlib
seaborn
urban-planning
housing-policy
nyc-open-data
data-visualization
policy-research
jupyter-notebook
statistical-analysis
public-policy
```

---

## **💡 PROJECT HIGHLIGHTS FOR LINKEDIN POST:**
```
🏘️ Just completed a comprehensive analysis of NYC housing enforcement patterns!

Analyzed 750K+ complaints and violations across 59 community districts, revealing:
📍 The Bronx housing crisis: rates 2-2.6x citywide average
📊 Strong enforcement correlation: R² = 0.925
⚠️ 58.5% of violations are hazardous conditions
📈 Seasonal patterns: June spike of 130,000+ violations

Key deliverables:
✅ 20-page technical report
✅ 15 publication-quality visualizations
✅ Fully reproducible Jupyter notebook
✅ Executive presentation deck

Tech stack: Python | Pandas | GeoPandas | Matplotlib | Seaborn

This project for NYU Furman Center demonstrates how data analysis can inform urban policy and address housing inequality.

#DataAnalysis #UrbanPlanning #Python #GeospatialAnalysis #PolicyResearch #DataScience
```

---

## **📌 RECOMMENDED COMBINATION:**

**GitHub Repository Name:**
```
NYC-Housing-Complaints-and-Violations-Analysis
