# AverageExtremes
A simple python program that utilizes the NOAA's API to retrieve temperature data for a selected US state over the past ~60 years.  

CreateDB retrieves the identification codes, coordinates, elevation, and start/end dates of all US stations and stores them in a SQLite table.

AverageExtremes prompts the user for a state, then retrieves the yearly minimum and maximum temperature across randomly selected stations in that state, stores them in a table, then graphs them in a scatter plot.
