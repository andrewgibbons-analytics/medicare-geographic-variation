# Medicare Geographic Variation Analysis

## Overview

This project examines county-level variation in Original Medicare spending and healthcare utilization using the Centers for Medicare & Medicaid Services Medicare Geographic Variation dataset.

The goal is to demonstrate how public healthcare data can be transformed into reliable metrics, comparative benchmarks, and actionable insights for population-health and value-based-care decision-makers.

## Business Question

Which U.S. counties exhibit both high standardized Medicare spending and elevated utilization indicators, and which service categories appear to contribute most to that variation?

The analysis treats emergency-department use, inpatient utilization, and readmissions as screening indicators for further investigation—not proof that utilization is avoidable or inappropriate.

## Planned Analysis

- Prepare a county-level analytical dataset
- Validate geographic level, population, suppression, and missing-value logic
- Compare county performance with state and national benchmarks
- Analyze standardized Medicare spending per beneficiary
- Evaluate emergency-department visits and inpatient utilization
- Examine acute hospital readmission rates
- Identify service categories associated with higher spending
- Develop a transparent county-level opportunity framework
- Publish an interactive Tableau Public dashboard

## Key Measures

- Original Medicare beneficiary count
- Standardized Medicare spending per capita
- Emergency-department visits per 1,000 beneficiaries
- Inpatient stays per 1,000 beneficiaries
- Acute hospital readmission rate
- Service-category spending and utilization measures

## Data Source

- [Medicare Geographic Variation – National, State & County](https://data.cms.gov/summary-statistics-on-use-and-payments/medicare-geographic-comparisons/medicare-geographic-variation-by-national-state-county)
- [CMS Data Dictionary](https://data.cms.gov/resources/medicare-geographic-variation-by-national-state-county-data-dictionary)
- Latest available data: 2024

## Tools

- SQL for transformation, validation, and analysis
- Tableau Public for visualization
- GitHub for documentation and version control
- Python may be used for supplementary quality checks or automation

## Important Limitations

- The spending and utilization measures primarily describe the Original Medicare population.
- Standardized spending removes certain geographic payment differences but does not adjust for differences in beneficiary health status.
- Suppressed and missing values must be handled explicitly.
- County comparisons are descriptive and should not be interpreted as causal.
- This project uses public CMS data and contains no proprietary employer information.

## Project Status

In development.
