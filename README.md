# Glass Classification

## Introduction
The classification of glass types can be incredibly important during criminological investigations. At the scene of a crime, glass can be used as evidence so it is important to correctly determine if two or more glass fragments originated from different sources. This can lead to identifying methods of escape, murder weapons, and other pieces of conclusive evidence.  
Our goal is to create a model that is successful in identifying glass samples obtained from a crime scene based on its weight percentages in 8 corresponding oxides. More specifically, we hope to answer the question: Given the weight percent of 8 glass oxides from a glass sample, which of the 6 glass types is it?  
The particular dataset we have chosen comes from the USA Forensic Science Service and classifies 6 types of glass based on their oxide content (see below for more details). The dataset also contains the refractive index of each glass observation.
Note that float-processing is a glass manufacturing process that creates a smooth, thick and uniform surface. In this dataset, there is no data for “vehicle_windows_non_float_processed” glass.

More details:
Glass Oxides (measured in weight percent in the dataset)
- Na: Sodium
- Mg: Magnesium
- Al: Aluminum
- Si: Silicon
- K: Potassium
- Ca: Calcium
- Ba: Barium
- Fe: Iron

Glass Types
- building_windows_float_processed
- building_windows_non_float_processed
- vehicle_windows_float_processed
- vehicle_windows_non_float_processed (**none in this dataset**)
- containers
- tableware
- headlamps