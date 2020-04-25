# DRT Real Time Analyser #

This is the report of DRT Real Time Analyser Project.

### Abstract ###

Characterization of batteries is very crucial for applications of battery. This is very important
to get the status of the battery, mainly the state-of-charge (SoC), or the remaining
charging in the battery, as well as state-of-health (Soh), or how much efficient capacity can
the battery handle compared to the factory capacity. Several techniques could be deployed
and have been developed. Impedance spectroscopy is a widely known techniques for characterization
of batteries. However, by itself, the impedance spectroscopy cannot provide an image
of the SoC or SoH of the battery, which requires other additional steps. The most prominent
method is modeling, in which an equivalent circuit is used to fit the impedance spectrum
of the battery, and the different values of the circuit are used to return the SoC and the SoH.
However, model-based approaches have a lot of shortcomings, as the model is dependent on
the material used in the battery, as well as different external factors mainly related to battery
setup. Another approach is a modeless technique, primarily the Distribution of relaxation
times (DRT). The impedance spectra is used as a feed to calculate a vector named distribution
of relaxation times (DRT). This DRT spectrum is the time domain representation of the linear
battery behaviour. In contrast to the impedance spectra, it can be used to directly simulate
the linear response of the battery. In this project special attention is given to the linear iterative
algorithms which are employed to solve the mathematically formulated problem of DRT.
This report also gives user an idea of the mathematics behind the algorithms used. The behaviour
of several algorithms is checked against 2 types of DUTs and results of simulations are
analysed.
