# ML_predict_the_electrical_energy
In this project we will build a model to predict the electrical energy output of a 
Combined Cycle Power Plant (https://en.wikipedia.org/wiki/Combined_cycle_power_plant), 
which uses a combination of gas turbines, steam turbines, and heat recovery steam generators to generate power. 
We have a set of 9568 hourly average ambient environmental readings from sensors at the power plant which we will use in our model.

using Google AutoML   https://cloud.google.com/automl-tables/docs/quickstart

The columns in the data consist of hourly average ambient variables:
- Temperature (T) in the range 1.81°C to 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in the range 25.36-81.56 cm Hg
- Net hourly electrical energy output (PE) 420.26-495.76 MW (Target we are trying to predict)
