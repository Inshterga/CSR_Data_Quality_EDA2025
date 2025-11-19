ESG Industry Analysis (2022)
# Project Overview

This project explores ESG (Environmental, Social, Governance) performance across 46 industries using publicly available ESG scores for 2022.
The goal is to understand industry-level patterns, evaluate dispersion in ESG performance, and identify areas where reporting or methodology may benefit from improvement.
The analysis was performed using spreadsheets.

# Repository Structure
ESG-Industry-Analysis-2022/
│
├── data/
│   ├── raw/                # Original dataset + documentation
│   └── clean/              # Cleaned dataset + missing-value research
│
├── analysis/
│   ├── methodology.md      # How the analysis was done└── insights_and_recommendations.md
|   ├── analysis.xlsx       # Summary stats
│   ├── visuals/            # Charts and exported visuals
│   └── insights_and_recommendations.md

│
└── docs/
    ├── project_outline.md
    └── next_steps.md

# Data Cleaning

Key cleaning steps included:

- Reviewing metadata and the data dictionary
- Correcting formatting inconsistencies
- Inspecting and resolving missing industry values
- Manually researching 13 companies with missing industry labels
- Keeping only one company with a clear specialization ("Alignment Healthcare LLC")
- Removing companies with no identifiable or multiple unrelated specializations

## The cleaned dataset is stored in:
/data/clean_data/clean_data.xlsx

## A detailed narrative of cleaning decisions is stored in:
/data/clean_data/cleaning_notes.md
/data/clean_data/Handling_missing_data.md

# Key Findings
1. Environmental scores lead across most industries

In 37 out of 46 industries, median Environmental scores exceed Social and Governance medians—often by a significant margin.
This pattern may reflect higher regulatory pressure and clearer reporting frameworks in environmental domains.

2. Large performance gaps within industries

Nine industries show ESG score dispersion above 750 points, revealing substantial differences among peer companies.

## Notable examples:

Technology: Adobe (621) vs. Microsoft (1533)
Energy: Chevron (637) vs. ConocoPhillips (1536)
Utilities: Xcel Energy (629) vs. Edison International (~1500+)
Hotels & Leisure: Allied Esports (600) vs. Airbnb (1475)
Beverages: Coca-Cola (601) vs. PepsiCo (1417)

## Top overall performers include:
Microsoft, Edison International, ConocoPhillips, and Airbnb.

3. Uneven ESG coverage across industries

Some industries—such as Technology, Biotechnology, and Health Care—are highly represented.
Others (e.g., Tobacco, Marine, Auto Components, Distributors) have very few companies reporting ESG data.

# Visuals

- Located in /analysis/visuals/.

1. Difference within industries- Total ESG Score Range by Industry
2. ESG pe inustry - Median Environmental, Social, and Governance Scores by Industry
3. Leaders and Laggards - Top and Bottom ESG Performers
4. Number of reported companies per industry

# Recommendations
## For Investors

Prioritize industries with higher ESG reporting density (Technology, Biotechnology, Health Care, Real Estate, Financial Services).
Better coverage reduces information risk and enables more reliable comparisons.

## For Companies in Under-Reported Industries

Limited ESG disclosure in industries like Tobacco, Marine, or Auto Components offers an opportunity.
Early adopters of transparent ESG reporting can position themselves as sector leaders.

## For Regulators & ESG Scoring Agencies

Given the consistently higher Environmental scores, Social and Governance scoring methodologies may benefit from:
- clearer definitions,
- improved sector-specific guidance,
- standardized disclosure expectations.

# Next Steps

Planned improvements:
- Add industry groupings based on international classification (GICS/NAICS).
- Explore changes from previous years (if data becomes available).
-(Future) Automate parts of the workflow using Python or SQL.
- Include financial performance variables to analyze the ESG–profitability relationship.