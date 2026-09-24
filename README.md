# World Bank internet use and income (2000–2024)

This repository contains a dated, 150-row snapshot of two World Development Indicators for Canada, Brazil, Germany, India, China, and the United States. Each row represents one country and year.

[Download the CSV snapshot](world-bank-internet-income-snapshot-2026-09-24.csv)

## Indicators

- NY.GDP.PCAP.CD — GDP per capita in current US dollars. This is not adjusted for inflation or exchange-rate changes.
- IT.NET.USER.ZS — Individuals using the Internet (% of population).

The CSV includes country code, country name, year, and one column for each indicator. Missing source values are left blank. Values can be revised by the World Bank after this snapshot was retrieved.

## Sources and attribution

Both series come from the World Bank's [World Development Indicators](https://datacatalog.worldbank.org/search/dataset/0037712/world-development-indicators):

- [GDP per capita (current US$)](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD)
- [Individuals using the Internet (% of population)](https://data.worldbank.org/indicator/IT.NET.USER.ZS)

Retrieved 2026-09-24 through the [World Bank Indicators API](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-about-the-indicators-api-documentation). The World Bank's WDI data is available under [CC BY 4.0](https://datacatalog.worldbank.org/public-licenses). Attribution: World Bank, World Development Indicators. This file is a static snapshot and is not an official World Bank publication.

## Explore the data

Compare country indicators and historical values in the interactive explorer at [GlobalDataTracker.com](https://globaldatatracker.com/).
# world-bank-internet-income-snapshot
A reproducible six-country snapshot of two World Bank WDI indicators (2000–2024).
