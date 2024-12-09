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
│   └── viewership_data.csv
├── SCRIPTS/
│   └── template_script.py
├── OUTPUT/
│   └── (for final results)
└── requirements.txt

```
## Instructions for Reproducing Results

1. **Clone the repository**:
   ```bash
   git clone https://github.com/fourchain40/DS4002-CS3.git
   cd project
2. **Install the required packages**
   ```bash
   pip install -r requirements.txt
3. **Complete the Analysis (User Tasks)*
   Task 1: Open SCRIPTS/template_script.py and complete the following tasks:
        - Clean the raw viewership data in DATA/viewership_data.csv (look for TODOs).
        - Train a double exponential smoothing model.
        - Forecast viewership for 2021-2024.
        - Calculate the percentage difference between forecasted and actual viewersh
4. **Save the Results**
  - Save your forecasted viewership data in OUTPUT/forecast_results.csv.
  - Save any visualizations in OUTPUT/visualizations/.
  - Write and save your final 5-page report as OUTPUT/final_report.pdf.

## References
Wikipedia, “Exponential Smoothing” https://en.wikipedia.org/wiki/Exponential_smoothing#Double_exponential_smoothing_(Holt_linear)
