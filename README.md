# HARModel

An implementation of the Heterogeneous AutoRegressive model from Corsi(2009)

If you find any bugs or think improvements can be made, please contact me at:

emilsjoerup@live.dk

TODO:
Expand the models to incorporate extra components such as jumps.

<<<<<<< HEAD
1: ADD a simulation routine.


Known bug(s):

1: Pressing the expand button on the Observations and vForecastComp vectors in a HARforecast object provides an error I can't seem to figure out. Luckily the vectors are accessible through `HARforecast$Observations` and `HARforecast$vForecastComp` respectively.
=======
Known bugs:
>>>>>>> Development

1: Pressing the expand button on the Observations and vForecastComp vectors in a HARforecast object provides an error I can't seem to figure out. Luckily the vectors are accessible through `HARforecast@Data[["Observations"]]` and `HARforecast@Data[["ForecastComparison"]]` respectively.
