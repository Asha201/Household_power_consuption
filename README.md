# Household_power_consuption

Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

This dataset contains 2075259 measurements gathered in a house located in Sceaux (7km of Paris, France) between December 2006 and November 2010 (47 months). Notes: 1.(global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3) represents the active energy consumed every minute (in watt hour) in the household by electrical equipment not measured in sub-meterings 1, 2 and 3. 2.The dataset contains some missing values in the measurements (nearly 1,25% of the rows). All calendar timestamps are present in the dataset but for some timestamps, the measurement values are missing: a missing value is represented by the absence of value between two consecutive semi-colon attribute separators. For instance, the dataset shows missing values on April 28, 2007.

### Attribute Information:

date: Date in format dd/mm/yyyy

time: time in format hh:mm:ss

global_active_power: household global minute-averaged active power (in kilowatt)

global_reactive_power: household global minute-averaged reactive power (in kilowatt)

voltage: minute-averaged voltage (in volt)

global_intensity: household global minute-averaged current intensity (in ampere)

sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).

sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.

sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.


### Goals
The focus of this analysis will be on global_active_power: the total active power consumed by the household (kilowatts).

### Visualization
Perform descriptive analytics on the global_active_power variable
Plot time series of global_active_power over the entire four year timeframe
Plot average monthly global active power
Plot typical daily consumption by month

### Forecasting
Apply and evaluate the following forecasting methods to the global_active_power time series:

Linear Regression (perfomed only as an exercise - not applicable to this dataset)
Seasonal AutoRegressive Integrated Moving Average (SARIMA)
Prophet Forecasting Procedure





