# Sports Viewership Time Series Analysis

## Project Overview
This project analyzes the impact of COVID-19 on the viewership of major American sports leagues (NFL, NBA, MLB, NHL) using double exponential smoothing. We aim to understand how viewership trends have evolved post-pandemic and whether each league has returned to pre-pandemic levels.

## Software and Platform

### Software:
- **Python 3.8 or higher**

### Required Packages
- **Pandas**: For data manipulation.
- **Numpy**: For numerical computations.
- **Matplotlib**/**Seaborn**: For creating visualizations.
- **Statsmodels**: To implement the double exponential smoothing model.
- **Jupyter Notebook**: For running and documenting the analysis.

### Platform:
- The project was developed and run on **MacOS** but should be compatible with **Windows** and **Linux** systems as well.

## Map of Repository Structure
```plaintext
Sports-Viewership-Post-COVID/
├── README.md
├── LICENSE.md
├── DATA/
│   ├── NFL.csv      # Imported NFL championship viewership data
│   ├── NBA.csv      # Imported NBA championship viewership data
│   ├── MLB.csv      # Imported MLB championship viewership data
│   ├── NHL.csv      # Imported NHL championship viewership data
├── SCRIPTS/
│   └── template_preprocess_script.ipynb
    └── template_modeling_script.ipynb
├── OUTPUT/
│   └── (for final results)
├── sports_viewership_covid.pdf  # Printed WEF reference
└── exponential_smoothing.pdf    # Printed ML Mastery reference
├── requirements.txt         # List of required Python libraries
└── rubric.pdf               # Rubric for the case study
└── hook_doc.pdf             # Hook document for the case study

```
## Instructions for Reproducing Results

1. **Clone the repository**:
   ```bash
   git clone https://github.com/fourchain40/DS4002-CS3.git
   cd project
2. **Install the required packages**
   ```bash
   pip install -r requirements.txt
3. **Complete the analysis**
   - Open SCRIPTS/template_preprocess_script.ipynb and template_modeling_script.ipynb and complete the following tasks:
   - Plot viewrship vs. year for each league (look for TODOs).
   - Train a double exponential smoothing model.
   - Forecast viewership for 2021-2024.
   - Calculate the percentage difference between forecasted and actual viewersh
4. **Save the Results**
  - Save your forecasted viewership data in OUTPUT/forecast_results.csv.
  - Save any visualizations in OUTPUT/visualizations/.
  - Write and save your final 5-page report as OUTPUT/final_report.pdf.

## References
- Wikipedia, “Exponential Smoothing” https://en.wikipedia.org/wiki/Exponential_smoothing#Double_exponential_smoothing_(Holt_linear)
- World Economic Forum, "The Impact of COVID-19 on Sports Viewership," https://www.weforum.org/agenda/2020/04/sports-covid19-coronavirus-excersise-specators-media-coverage/
- Machine Learning Mastery, "Exponential Smoothing for Time Series Forecasting," https://machinelearningmastery.com/exponential-smoothing-for-time-series-forecasting-in-python/
