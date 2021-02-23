
# RenewableEnergy
https://renewable-energy-herokuapp.herokuapp.com/

### About the Project
##### In this project, we analyzed 3 key points
    * Usage of renewable energy all over the World.
    * How are the relations between GDP of each countries and renewable energy generation and consumption?
    * Display the effect of renewable energy generation on air pollution and death rate by years.

### Data Sources
* https://ourworldindata.org/renewable-energy
* https://www.irena.org/documentdownloads/publications/irena_measuring-the-economics_2016.pdf
* https://ourworldindata.org/air-pollution
* https://ourworldindata.org/grapher/renewable-energy-investment-of-gdp
* https://justenergy.com/blog/7-types-renewable-energy-future-of-energy/

### Technologies used
* Python: Pandas, Flask
* Javascript 
* HTML, CSS, Bootstrap
* D3, Chart-js, Plotly
* Webscraping - chromedriver version 86
* Mongo cloud

### Usage
* Make sure all the requirements from the requirements.txt are up to date.
* For Database Setup 
    - Config.py - Need to provide the Mongocloud database username and password
    - Chromedriver.exe (version 86) to be installed and provide the executable path in datascrape.py
    - Run datacleanup.py
* For running the application
    - Need to provide the Mapbox APIkey in the config.js
    - Run app.py

### Remote Acess
* Heroku
