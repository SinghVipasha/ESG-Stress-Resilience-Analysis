# ESG-Stress-Resilience-Analysis
# ESG and Market Downside Resilience

### Evidence from S&P 500 Firms

##  Overview

This project investigates whether companies with higher ESG scores demonstrate greater resilience during periods of market stress.

Using S&P 500 firm-level data, I analyse stock performance on extreme negative market days and compare outcomes across ESG groups, while accounting for sector composition and firm size.

##  Research Question

Do high-ESG firms experience smaller losses during market downturns compared to low-ESG firms?

##  Data

* S&P 500 daily stock prices (2024–2025)
* S&P 500 index data for market returns
* ESG scores (2023)
* Company sector and market capitalization

##  Methodology

1. Compute daily stock and market returns
2. Define **stress days** as bottom decile of market returns
3. Classify firms into **High vs Low ESG** using median split
4. Compare mean returns on stress days (t-test)
5. Conduct robustness checks:

   * Sector-wise comparison
   * Regression controlling for firm size

##  Key Findings

* High-ESG firms show **smaller average losses** during stress periods
* The difference is statistically significant
* Much of the effect is explained by **sector composition**
* ESG retains a **modest independent effect** after controlling for size

##  Limitations

* Static ESG scores
* Large-cap sample only
* Observational (not causal)


##  How to Run

1. Clone repository
2. Install dependencies
3. Run Jupyter notebook in `/notebooks`

##  Author

Vipasha Singh

## 📄 Related Paper

Available on ResearchGate: <add link>
