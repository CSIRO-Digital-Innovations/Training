### Important Elements of APSIM Next Generation

#### Objective
Experienced APSIM users understanding how to change their approaches to modelling to take advantage of the features of APSIM Next Generation

#### Background Knowledge
* working knowledge of APSIM NG or Classic
	* we will not be explaining all elements of the model user interface
	* we will not be explaining APSIM science

#### Materials/Setup
* APSIM Next Generation should be installed on participant's PC


#### Key Messages



###### Reporting is Different
* Much of the APSIM UI makes use of capabilities of .NET.  This reduces much of the coding burden, but does change the way we do reporting
* We make much more of the model's state variables and internal variables available to the user.  Therefore, we don't provide a list of outputs.
* We use intellisense in the Report model to search through the model to find output variables
* We can do calculations within the report model to avoid calculation of outputs in scripts - this is the preferred approach
* Output is stored in a database file rather than a text file. This can be easily read by python or R.  Data can be exported to Excel.


###### Replacements Replace Shortcuts
* Shortcuts in APSIM Classic were powerful but dangerous, and made maintenance costly
* We use a Replacements folder to overwrite models at runtime
* Alternatively, Experiments can serve the same purpose as Shortcuts, but are much more powerful and safe


###### Experiments are Powerful
* Anything more complicated than a single simulation should generally be achieved using an experiment
* Experiments can be full or partial factorials
* Factors can be simple (e.g. N Rate) or complex (e.g. Site = met file + soil) types
* Any simulations submitted to validation sets should be configured as experiments

###### Graphing is Improved
* Graphing is faster
* Colours follow a published standard for people with vision impairment
* Formatting can be according to simulation name, experiment name, factor name, etc.


###### Sensitivity Analysis
* Two approaches currently provided (Morris, Sobol)
* Recommend starting with Morris, and with assistance from experienced users

###### Observed Data
* If data is to be submitted to APSIM version control, observed data must be provided in standard format (e.g. as used to create Observed vs Predicted Graphs)
* Data in this format is used to calculate validation statistics and documentation
* Tutorials on Day 2 will go into detail

###### Exploring Crop Model Structure
* Crop models are developed using the Plant Modelling Framework
* Crop model structure can be studied in the user interface
* This is useful for 1) understanding the model equations and 2) locating relevant output variables

###### Services for Soil and Met Data are Available
* Data services are available for soil and weather data via the APSIM user interface

