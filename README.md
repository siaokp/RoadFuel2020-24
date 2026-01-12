UK Road Fuel Stock Levels (2020–2024)

This project analyses UK road fuel stock levels using official government data, combining time-series analysis with spatial visualisation.

Data sources

Department for Energy Security and Net Zero (DESNZ):
Average road fuel sales, deliveries and stock levels

Office for National Statistics (ONS):
International Territorial Level (ITL) Level 2 boundaries

Methodology

Five years of sub-regional fuel data (2020–2024) were processed in Python.

Data was aggregated at:

National level for time-series analysis

ITL2 level for spatial analysis

Due to incomplete regional coverage, sales and delivery metrics were analysed at national level only.

Stock level percentages were used for ITL2 mapping, as they provide consistent spatial coverage.

Outputs

Python notebook for data cleaning and aggregation

National time-series chart of fuel stock levels

ITL2 geographic heatmap showing regional variation over time (Tableau)

Key insight

Fuel stock levels show clear national shocks during major events (COVID-19 lockdowns, 2021 supply disruptions, and the 2022 energy crisis), with noticeable regional variation across ITL2 areas.

Note on spatial coverage:
Sales and delivery metrics as seen in tableau heatmaps only display data from 2020-2022 due to incomplete ITL2 coverage in later years. Stock level percentages were used instead, as they provide consistent regional reporting across the full time period.