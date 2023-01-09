# Emissions_with_Dash

### Requirenments

Description: Emission dashboard to explore individal country contributions, and identify the most polluting nations over time.

- Graph 1: Shows all countries total emissions by population and GDP. Date is adjustable with a slider.  
- Graph 2: Shows detailed emission values for the selected country from Graph 1 over time. There should be an option to select total or per capita values.  
- Graph 3: Shows the top 10 most pollutant nations over time.

### Dependencies

- Pandas: to read/clean and extend the default dataset
- Dash/JupyterDash: framework used to create the web dashoard
- Plotly: to supply the visual graphs to Dash

### Information about the combined dataset from the World Bank

Source: https://databank.worldbank.org/source/world-development-indicators

Contains data in the following categories:

- Country stats:
  - Population, total
  - GDP per capita (constant 2015 US$)  
    
    
- Emission data:
  - CO2 emissions (kt)
  - CO2 emissions (metric tons per capita)
  - Methane emissions (kt of CO2 equivalent)
  - Nitrous oxide emissions (thousand metric tons of CO2 equivalent)
  
### Result

![emission_dash_screenshot.png](/emission_dash_screenshot.png)