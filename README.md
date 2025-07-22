# ginicoefficienteumap

![cover](dashboard/gini_map_preview.png)


An EDA based on World Bank's income inequality data (Gini Index) between 2014 and 2024. The analysis is narrowed down to the European Union member states to stay consistent with regional socio-economic policy relevance.

Pandas and GeoPandas were used for data cleaning and reshaping, and Plotly was used to create an interactive choropleth map that visualizes inequality trends over time.

The Gini Index reflects income distribution within a country. Through this analysis, we observed that countries like Slovenia, Czechia, and Slovakia consistently maintained lower inequality levels, while others such as Bulgaria, Spain, and Turkey showed relatively higher inequality scores. The map allows users to view these changes year by year and spot broader patterns over the decade.

The Netherlands, for example, remained relatively stable throughout the period, showing only minor changes in inequality levels.

The interactive map is embedded in the notebook and allows users to select any year from 2014 to 2024. Country-level values are available on hover, and the map is restricted to EU member countries.

The dataset is located in the "data" folder.

The Jupyter notebook is in the "notebook" folder.

The interactive dashboard is saved as an HTML file in the "dashboard" folder.

No essay is included in this project since the year-by-year visualization provides a self-explanatory view of the inequality dynamics.

**Resources**

- [Eurostat: Gini coefficient of equivalised disposable income - EU-SILC survey](https://ec.europa.eu/eurostat/databrowser/view/tessi190__custom_17551990/default/table)

