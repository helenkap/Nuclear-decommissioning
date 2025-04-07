# Nuclear-decommissioning
Work with databases on the status of nuclear facilities decommissioning 

## Functions 
- reading data from excel files
- direct connection to data sources via API
- data preparation (categorization of nuclear facility types - research reactors, nuclear power reactors, fuel cycle facilities, cleaning empty columns and rows)
- calculation of the facility years in operation, age (medians, maximum or minimum)
- prediction of number of facilities entering decommissioning based on age
- data visualization 
- filtering options (faciity types, age, location, etc.)

### Requirements 
Python 3.12
Libraries:
- pandas 
- openpyxl #reading/writing to excel (.xlsx)
- requests # connection to API
- gradio or seaborn #data visualization
- numpy #numeric calculations
