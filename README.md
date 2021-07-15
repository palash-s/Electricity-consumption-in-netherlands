[![license](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://github.com/palash-s/Electricity-consumption-in-netherlands/blob/main/LICENSE)

# Electricity-consumption-in-netherlands
 ETA and Time Series analysis on data from one of the power providers in NL


## Data Description
link to the data - [kaggle](https://www.kaggle.com/lucabasa/dutch-energy)

The energy network of the Netherlands is managed by a few companies. Every year, these companies release on their websites a table with the energy consumption of the areas under their administration. The companies are

- Enexis
- Liander
- Stedin
- Enduris
- Westlandinfra
- Rendo
- Coteq
The data are anonymized by aggregating the Zipcodes so that every entry describes at least 10 connections.

This market is not competitive, meaning that the zones are assigned. This means that every year they roughly provide energy to the same zipcodes. Small changes can happen from year to year either for a change of management or for a different aggregation of zipcodes.

Content
Every file contains information about groups of zipcodes managed by one of the three companies for a specific year.

Acknowledgements
All the data are taken from the following websites:

- https://www.enexis.nl/over-ons/wat-bieden-we/andere-diensten/open-data
- https://www.liander.nl/partners/datadiensten/open-data/data
- https://www.stedin.net/zakelijk/open-data/verbruiksgegevens
- https://data.overheid.nl/dataset/enexis-verbruiksdata (up to 2016)
- https://www.enduris.nl/over-enduris/energietransitie/open-data.htm
- https://www.westlandinfra.nl/over-westland-infra/open-data
- https://www.rendonetwerken.nl/algemeen/opendata/disclaimer/beschikbare-data/
- https://coteqnetbeheer.nl/Over-Coteq/Open-data

- Some processing was made with the code available at: https://github.com/lucabasa/kaggle_dutch_energy/blob/master/raw_data_cleaning.ipynb

The translation of the column names and descriptions was made by a non-native speaker.
