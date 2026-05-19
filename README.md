# AI-Immigration
# Project Title

## 👥 Team Members

- Ai Nakayama (@ainakayama90) - Role/Responsibility
- Akyla Imanalieva (@akylaimanalieva) - Role/Responsibility
- Aston Chia (@AstonChia99) - Role/Responsibility
- Ririka Noda (@RirikaNoda) - Role/Responsibility
- Mami Umeki (@mamiumeki2001) - Role/Responsibility


## ❓ Research Question & 🎯 Hypothesis

Topic: How the US-Iran conflict reshape oil trade routes 

Aim to answer: 
1)        Did tanker traffic through the Strait of Malacca change?
2)        Which chokepoints absorbed rerouted flows?
3)        Which exporters replaced Gulf crude?

## 📁 Data Sources

| Source | Description | URL |
|--------|-------------|-----|
| Marine Traffic | Live worldwide marine traffic reporting | (https://www.marinetraffic.org/MALACCA%20STRAIT/ship-traffic-tracker) |
| IMF | Brief description | [IMF Data Portal](https://www.imf.org/en/Data) |
|Port of Singapore Data|Port of Singapore, Tanker Arrival, Total, Monthly up till May 2026|https://data.gov.sg/datasets/d_9adb5ace517591edd9a8c88291ac1f1c/view| 

### Data Sources Details

|https://aisstream.io/| 
|https://github.com/aisstream/Projects-Using-aisstream.io|
|CSV file for Port of Singapore available on website in abovementioned| 

#### D.1 World Bank  
**Variables:** e.g., NY.GDP.MKTP.CD, SE.PRM.CMPT.ZS

**Granularity:** e.g., Annual data by Country

#### D.2 IMF  
**Variables:** e.g., Consumer Price Index, Interest Rates

**Granularity:** e.g., Quarterly data by Region

## 📂 Folder Structure

### Folder Structure Notes
- All projects MUST follow this standardized folder structure
- `data/raw/` - **NEVER** edit manually; store original data here
- `data/clean/` - Cleaned datasets ready for analysis
- `data/temp/` - Temporary files (can be deleted)
- `notebooks/` - Jupyter notebooks for analysis
- `src/` - Python code
- `reports/` - Final outputs: plots, summaries, model files
- `docs/` - Project documentation, README, presentations

### Folder Structure Tree

```tree
project/
├── data/
│   ├── raw/                   # Original, immutable data
│   │   ├── world_bank_raw.csv
│   │   └── imf_financials_raw.csv
│   ├── clean/                 # Cleaned, transformed data
│   │   ├── world_bank_clean.csv
│   │   └── imf_merged_clean.csv
│   └── temp/                  # Temporary working files
├── notebooks/                 # Jupyter notebooks for exploration
│   ├── 01_eda_worldbank.ipynb
│   ├── 02_regression_analysis.ipynb
│   └── 03_policy_simulations.ipynb
├── src/                       # Production-ready scripts
│   ├── download_worldbank.py  # API/Scraping script
│   ├── clean_data.py          # Merging and cleaning logic
│   └── visualize_worldbank.py # Chart generation functions
├── reports/                   # Final outputs
│   ├── figures/               # Saved .png plots for the memo
│   │   ├── gdp_trend_line.png
│   │   └── debt_distribution.png
│   ├── policy_memo_final.pdf
│   └── regression_results.txt
└── docs/                      # Documentation
    ├── data_details.md        # Data dictionary & column definitions
    ├── data_architecture.md   # Pipeline logic and join keys
    ├── policy_context.md      # Political background & stakeholders
```

## 📅 Timeline

| Milestone | Deadline | Deliverable |
|-----------|----------|-------------|
| M1        | Date     | Output      |
| M2        | Date     | Output      |
| M3        | Date     | Output      |

## 🤝 Contributions

| Member | Tasks |
|--------|-------|
| Name   | Description of contributions |
| Name   | Description of contributions |

## 🔗 References
- Link to methodology references
