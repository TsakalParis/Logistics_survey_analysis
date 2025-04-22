# Logistics Survey Analysis

A comprehensive statistical analysis of Total Quality Management (TQM) implementation in the logistics sector.

## 📊 Overview

This is a project where I did the statistical analysis for a client's thesis in Public Management and Business Administration. The survey was created by the client and was sent to people who work in the logistics sector. The data was translated into English by me. Part of the content is what the client requested. The survey was conducted using Google Forms, so my job was to provide additional information, rather than just have the standard insights that Google provides by default.

The base of this case study is to see the degree to which Total Quality Management is used in the logistics sector.

## 🔍 Analysis Steps

This analysis contains the following steps (not in order):

- Process dataframe
- Generalize dataframe
- Cronbach's alpha reliability coefficient
- Finding Correlations
- Function to calculate p-value from pearson correlation table
- Function that filters values in dataframe based on condition
- Checking correlations statistical importance using p-value
- Displaying the important correlations
- Confidence Interval for Correlation
  - Step 1: Create functions
  - Step 2: Pass desired values
- Creating Heatmap
- Describing Data
- Coefficient of Variation
- Confidence Interval for Mean
- Median and Mode
- Skewness
- IQR
- Kurtosis
- Data Visualization
  - Histogram
  - Box Plot
  - Violin Plot

## 🚀 Key Findings

Based on the analysis, several key insights emerged:

- Strong correlation between experience level and age demographics (e.g., professionals with up to 3 years of experience tend to be younger, aged 18-30)
- Management positions correlate with 20+ years of industry experience
- TQM implementation scores show high correlation with international quality standards
- Lower TQM adoption observed among older professionals (51-60 years)
- Larger companies (200+ employees) and organizations with higher revenue (10M+ euros) demonstrate stronger TQM implementation

The analysis also examined four key dimensions:
1. Quality System Implementation
2. Applied TQM Practices
3. Company Culture
4. Goals Achievement

## 📋 Technical Implementation

The analysis utilizes several Python libraries and statistical techniques:

```
pandas
numpy
statsmodels
matplotlib
seaborn
scipy
pingouin
```

Key statistical methods employed:
- Cronbach's alpha for scale reliability
- Pearson correlation with p-value significance testing
- Fisher's Z transformation for correlation confidence intervals
- T-tests against reference values
- Distribution analysis (skewness, kurtosis, IQR)

## 🖥️ Usage

To run the analysis:

```bash
# Clone the repository
git clone https://github.com/TsakalParis/Logistics_survey_analysis.git
cd Logistics_survey_analysis

# Install the required dependencies
pip install -r requirements.txt

# Run the analysis
python logistics_analysis.py
```

## 🔬 Analysis Components

### Data Processing
- Converting categorical responses to numerical values (0-4 scale)
- Creating dummy variables for demographic categories
- Calculating TQM scores across multiple dimensions

### Scale Construction
- Quality System Score
- Applied TQM Score
- Company Culture Score
- Goals Achievement Score

### Statistical Analysis
- Descriptive statistics for all dimensions
- Correlation analysis with significance testing
- Confidence intervals for means and correlations
- Distribution characteristics analysis

### Visualization
- Correlation heatmaps with statistical significance
- Distribution histograms with density curves
- Box plots for outlier detection
- Violin plots for distribution comparison

## ⚠️ Methodology Notes

The analysis employs a systematic approach to examine TQM implementation:

1. **Scale Reliability**: Cronbach's alpha confirms internal consistency of measurement scales
2. **Correlation Analysis**: Pearson correlations with significance testing (p < 0.05)
3. **Group Comparisons**: Analysis across company size, experience level, and management status
4. **Distribution Analysis**: Examination of response patterns and variability

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*Note: This analysis was conducted for academic research purposes. The survey was created by the client, and the data was translated into English for analysis.*
