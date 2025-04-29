# Aviation Risk Analysis

**Author:** Beatrice Ndanu Kiilu  
**Date:** April 28, 2025

## Project Overview

This project provides a data-driven analysis to support a company's decision in selecting the **lowest risk aircraft** for purchase. It leverages historical aviation accident data to uncover trends, identify high- and low-risk manufacturers, and guide safer investment in aircraft.

## Business Problem

The company is expanding into aviation and seeks to minimize liability by selecting safer aircraft. The analysis addresses:

- Which aircraft types and manufacturers are associated with fewer or less severe accidents?
- How have aviation incidents changed over time?
- Are there seasonal patterns in accident frequency?

## Data Description

- **Source**: National Transportation Safety Board (NTSB)
- **Range**: 1962 to 2023
- **Key Features**: Aircraft make/model, accident date, severity, location, and more

## Data Cleaning & Preparation

- Parsed and extracted `Accident Year` from event dates
- Standardized and cleaned text fields (`Make`, `Model`)
- Handled missing values as appropriate for accurate aggregation

## Key Insights

- **Safest Manufacturers**: Hughes, Bellanca, Grumman, Robinson, and Mooney showed consistently low incident severity.
- **Most Risk-Prone**: Cessna, Piper, and Beech had higher rates of serious and fatal accidents.
- **Seasonal Risk Trends**: Summer months saw higher accident rates, likely due to increased flight activity.

## Business Recommendations

1. **Invest in Aircraft from Hughes, Bellanca, Grumman, Robinson, and Mooney** due to their strong safety records.
2. **Avoid models from Cessna, Piper, and Beech** given their elevated fatality and incident rates.
3. **Consider Seasonality** when assessing flight risks or planning operational changes.
## Files
- `Aviation_Analysis.ipynb` – The main notebook with code, visuals, and insights
