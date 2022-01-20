# GDP per capita Bar Chart Race

Create a Bar Chart Race to show the evolution of GDP per cápita at current market prices by NUTS 2 or NUTS 3 regions for the period 2010-2019

The data can be downloaded from [Eurostat](https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=nama_10r_2gdp&lang=en)

@author: Sergio Pereira

@email: <sergio@sergiopereira.gal>


## Libraries

This project uses [Pandas](https://pandas.pydata.org/) and [Bar_Chart_Race](https://www.dexplo.org/bar_chart_race/)


## Data sources

This project takes two files downloaded from Eurostat, the statistical office of the European Union.

This two datasets are used:

- Eurostat [GDP) at current market prices by NUTS 3 regions](https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=nama_10r_3gdp&lang=en)
- Eurostat [Average annual population to calculate regional GDP data](https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=nama_10r_3gdp&lang=en)

Another file is the NUTS classification (Country, NUT1, NUT2, NUT3) for each entity in the previous files. This file only contains info for Spain and Portugal, and has been created manually based on this file from Eurostat: [Area by NUTS 3 region](https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=reg_area3&lang=en)