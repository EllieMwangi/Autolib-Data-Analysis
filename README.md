# Autolib Data Analysis
Processing stations data to understand electric car usage over time
## Specifying data analysis question
Identify the most popular hour of the day for picking up a shared electric car (Bluecar) in the city of Paris over the month of April 2018.

Additional research questions:
- What is the most popular hour for returning cars?
- What station is the most popular?
 - Overall?
 - At the most popular picking hour?
- What postal code is the most popular for picking up Blue cars? Does the most popular station belong to that postal code?
  - Overall?
  - At the most popular picking hour?

## Recording experimental design
1. Load datasets
2. Check and deal with missing data
3. Check and deal with duplicates
4. Drop unnecessary columns
5. Create dataframe containing Paris data only.
6. Create datetime feature from available columns
7. Perform univariate analysis of available features
8. Filter out paris data to contain only stations with rental operational status

## Data Relevance
Data was extracted from opendataparis.com, where the Autolib availability information was
available in real-time. The accessed database was the following:
-  Name: Stations Autolib: Disponibilité en temps réel
-  Producer : Autolib
- Date : April 1 - April 9 2018
-  License : Open Database License

