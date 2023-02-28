# Combined Cycle Gas Turbine Power Plant Electrical Energy Output Prediction
This predicts electrical energy output from a Combined Cycle Gas Turbine Power Plant. 
A Combined Cycle Gas Turbine (CCGT) power station is a highly efficient and flexible source of electricity generation. It combines a gas turbine and a steam turbine in a single power plant, allowing for the utilization of waste heat to produce additional power.

This work on the Combined Cycle Power Plant Data Set on the UCI website [link](https://archive.ics.uci.edu/ml/datasets/combined+cycle+power+plant). Using random forest regression, I created a prediction model with r2_score/accuracy of 99%. Given the temperature (°C), exhaust vacuum (cm Hg), ambient pressure (millibar) and relative humidity (%), this model predicts the electrical energy output from a Combined Cycle Gas Turbine Power Plant. 

Variable Information:

Features consist of hourly average ambient variables
- Temperature (T) in the range 1.81°C and 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 millibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in teh range 25.36-81.56 cm Hg
- Net hourly electrical energy output (EP) 420.26-495.76 MW
