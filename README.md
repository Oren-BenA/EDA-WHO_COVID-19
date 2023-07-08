# EDA_COVID-19-WHO-Data
# This project was my first project in a "Practical Data Science" program I am taking (starting from February-2023)
# It's goal was to analyze Two World-Health-Organization table files reporting new COVID-19 cases and deaths in two formats:
# Format 1: per country, COVID19 Total number of new cases and new deaths, per day, starting from 01-01-2020 till present time
# Format 2: per country, cumulative data table: total number of cases, total number of deaths, in present time
# The idea was to explore these files using basic Python, without making use of any of the useful Python packages (pandas and others)
# The project defines a COVID-19 class that upon object instatiation, of a COViD-19 Class, the CSV file/s are read and two Dictionaries are created and serve the other class methods downstream;
# Class Methods defined:
    #1 - Receives a dictionary and returns the first COVID-Case per country
    #2 - Receives a dictionary and a name of a country and returns country name and the total number of local-Max and local-Min of number of COVID cases per country; 
       # This can be used as a proxy for the number of COVID-19 bursts/waves per country
    #3 - A method that creates a country dictionary of covid-19 cases/deaths data per month per 100K residents 
    
  
