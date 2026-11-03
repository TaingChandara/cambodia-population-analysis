# Cambodia Population Analysis — 2024

A Power BI project exploring Cambodia’s population and household distribution across provinces, regions, and urban/rural areas using government open data.

## Dashboard Preview

<img width="1557" height="747" alt="Dashboard" src="https://github.com/user-attachments/assets/018c9d9a-a7e9-4a01-a794-48c59e9f4736" />


## Project Objectives

- Compare population sizes across provinces.
- Explore urban and rural population distribution.
- Compare population across Cambodia’s four regions.
- Analyze male and female population distribution.
- Examine household counts and average household size.

## Data Source

[Distribution of Population by Area, Region, Province, and Sex, Cambodia 2024](https://data.mef.gov.kh/datasets/pd_68511e8f1b4d5f000166ac32)

Accessed through Cambodia’s Data for Economic and Finance portal.

The imported dataset contains 31 rows covering:

- 25 provinces and the capital combined.
- 2 area categories: Urban and Rural.
- 4 regions.

These geographic levels describe overlapping populations and must be analyzed separately to avoid double counting.

## Tools Used

- **Power Query:** Data preparation and filtering.
- **DAX:** Population and household calculations.
- **Power BI Desktop:** Report design and visualization.

## Data Preparation

1. Assigned appropriate numeric, text, and Boolean data types.
2. Created separate reference queries for provinces, areas, and regions.
3. Added a validation column to check whether male and female counts sum to the total population.

## Key Measures

- Total Population
- Total Households
- Male Population
- Female Population
- Average Household Size

Overall average household size is calculated as total population divided by total households, rather than a simple average of provincial household sizes.

## Selected Findings

Based on the Urban and Rural records:

- Urban population: **7,172,206**, approximately **41.5%**.
- Rural population: **10,108,337**, approximately **58.5%**.
- The rural population exceeds the urban population by approximately **2.94 million people**.

These results describe population distribution and can support further research into service coverage and geographic market size.

## Limitations

- The dataset represents 2024 and does not support analysis of population growth over time.
- Population size alone does not establish purchasing power, demand, or profitability.
- Population density requires additional land-area data.
- The report uses an imported data snapshot; it is not a live dashboard.

## Viewing the Report

View the screenshot above for a quick preview. To explore the report, download `Cambodia_Population_2024.pbix` and open it in Power BI Desktop.

## Author

**Taing Chandara**  
Data Analyst / BI Portfolio
