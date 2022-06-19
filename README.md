# Battery-Management-Systems-Equivalent-Circuit-Cell-Model-Simulation--Tuning-an-ESC-Cell-Model

If you wish to create an Rint model, simply set rcValues equal to the value of R0 (in milliohms).

If you wish to create a Thévenin model, define rcValues to be a vector having three elements. The first element is R0 (in milliohms),
the second element is R1 (in milliohms), and the third element is C1 (in kilofarads).

If you wish to create an extended Thévenin model having additional resistor-capacitor branches, then define rcValues to 
be a vector where the first element is R0 in milliohms, the even-index elements (rcValues(2:2:end)) are resistor values for
the resistor-capacitor branches, in milliohms, and the remaining odd-index elements (rcValues(3:2:end)) are capacitor values for
the resistor-capacitor branches, in kilofarads.
