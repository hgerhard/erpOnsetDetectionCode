Code for finding onset times in ERP data and for calculating jackknifed error estimates on those onset times. 

Implemented by Holly Gerhard (2014-2016)

———
See the example script example.m which generates a hypothetical set of ERPs from multiple participants and estimates the mean ERP’s onset time and associated error estimate across subjects.

The default onset calculation is based on a method described by Osman, Bashore, Coles, Donchin, & Meyer (1992) On the transmission of partial information: inferences from movement-related brain potentials, JEP: Human Perception & Performance, 1, 217-232.

Other onset calculations are also provided, such as those described by Luck & Kappenman (2011) in The Oxford Handbook of Event-related Potential Components.

Jackknifed errors on ERP onset times are implemented as described by Miller, Ulrich, & Schwartz (2009), Why jackknifing yields good latency estimates, Psychophysiology, 46, 300-312.