# Crime In India
This project contains data for crime in India for 2016 and a Shiny app to visualise the data.
The data has been collected from the National Crime Records Bureau of India (NCRB). 

The data includes the **number of incidents** for every type of crime recognized under the **Indian Penal Code (IPC)** for every state in India.

## Shiny app
The app can be accessed [here](https://lakshyaag.shinyapps.io/CrimeInIndia/).
### Layout of the app
1. **Overview** - Provides a high-level view of number of incidents in every state for 2016.
2. **Crime-wise** - Provides insights on number of incidents of a particular offence under the Indian Penal Code for every state.
3. **State-wise** - Provides insights on the offences with highest number of incidents for a particular state.
4. **Indian Penal Code - Section Descriptions** - A table that allows searching by IPC section or crime description. 

## Libraries used
1. `tidyverse` & associated libraries
2. `shiny` & associated libraries
3. [`bbplot`]([https://github.com/bbc/bbplot](https://github.com/bbc/bbplot))

## Files
1. `clean_crime.ipynb`	- this notebook cleans and preprocesses the raw data to transform it into a tidy dataset, which is further used in visualization
2. `app.R` - this project contains the code for visualizing the crime statistics and creating visualizations on-the-fly.
3. `crime_2016_tidy.csv` - this file contains the cleaned dataset that is used in the visualization. 

## TO-DO

 - [ ] Add crime rates to the visualization
 - [ ] Gather data for more years to enable temporal analysis
 - [ ] Work on improving the user experience

#### Please drop me a message or create a pull request if you have any suggestions.
