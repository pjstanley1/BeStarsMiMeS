# Longitudinal Field Calculations

The longitudinal magnetic field strengths are calculated in the Colab notebook [06-LongitudinalField](https://github.com/veropetit/BeStarsMiMeS/blob/master/06-LongitudinalField.ipynb)

We make use of [specpolFlow](https://github.com/folsomcp/specpolFlow) and its Bz.py function. The unchanged parameters are as follows:

* cog = I
* norm = auto
* lambda0 = 500nm
* geff = 1.2
* bzwidth = None

The velocity range was set between $\pm$vsini of the star. The code was then ran for every star and for the various models described in [00-3-LSDProfileCalculation](https://github.com/veropetit/BeStarsMiMeS/blob/master/00-3-LSDProfileCalculation.md)
 


