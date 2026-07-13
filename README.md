# ladybeetles
These data files and code are associated with the scientific article, "Freeze tolerance of a beneficial lady beetle, Hippodamia convergens."
This material is under the same copyright protections as the article itself.

# RCode file
The code can be run in R v4.5.2, and was used to conduct statistical analysis from the data files below.

# Data files
These are used for statistical analysis and figure generation in the RCode file.

## SCP.csv
This reports supercooling point (SCP) for beetles during a gradual cooling protocol. Beetles were kept at 4C for 1 week prior to the SCP measurements.Each row pertains to a different individual, with information provided for each variable (column heading), as described below. 

VARIABLE: DESCRIPTION
#Beetle ID: Unique beetle identifier<br>
#Mass: Weight of the beetle in grams<br>
#Sex:Whether the beetle was male (M) or female (F)<br>
#SCP: Supercooling point (SCP) in degrees Celcius, the temperature at which internal ice formation begins
#Alive: Whether the stonefly was alive (Yes) or not (No) following thawing<br>

## InoculativeFreezing.csv
This summarizes the number of beetles that were frozen, chilled, handling controls, and whether they survived or did not after exposure to -3, -5, or -8C for 20 hours. The tempeature is recorded in the first row, and the count of beetles in each cateory is listed below the temperature.
