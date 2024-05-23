# Foreign Direct Investment in Viet Nam

## Description
The report provides an overview of the foreign direct investment (FDI) situation in Vietnam from 2015 to 2022 and uses the ARIMA model to forecast for 2023 to 2025. The report emphasizes the significant role of FDI in promoting economic growth, expanding production scale, and improving Vietnam's trade balance.

## Table of Contents
- [Project Structure](#Project-Structure)
- [Dashboard Preview](#Dashboard-Preview)
- [Additional Notes](#Additional-Notes)
- [Contact](#Contact)

## Project Structure
```
Foreign-Direct-Investment/
├── data/
│   ├── data-raw/
│   │   ├── fdi_country_partners_en.csv
│   │   ├── fdi_industry_vi.csv
│   │   └── fdi_provinces_vi.csv
│   └── data-clean/
│       ├── fdi_country_partners_en_clean.csv
│       ├── fdi_industry_vi_clean.csv
│       └── fdi_provinces_vi_clean.csv
├── source/
│   ├── FDI-Industry.ipynb
│   ├── FDI-Partners.ipynb
│   └── FDI-Provinces.ipynb
├── Foreign-Direct-Investment.docx
├── Foreign-Direct-Investment.pbix
└── README.md
```
Each .ipynb file in each category will process the raw data sets in the data-raw folder and produce the complete data sets in the data-clean folder.
- Foreign-Direct-Investment.docx: Report file
- Foreign-Direct-Investment.pbix: Create Dashboard with Power BI

## Dashboard Preview
- Summary Dashboard

- Partner Dashboard
- Provinces Dasboard
- Industries Dashboard

## Additional Notes
This project uses data from the followings source:  
- Published by: Open Development Vietnam
- Link: https://data.vietnam.opendevelopmentmekong.net/dataset/fdi-investment-in-vietnam-2015-2022

## Contact
If you have any questions, please contact via email at ngohuan18112002@gmail.com

