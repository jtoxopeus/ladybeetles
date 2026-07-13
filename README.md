# ladybeetles
These data files and code are associated with the scientific article, "Freeze tolerance of a beneficial lady beetle, Hippodamia convergens."
This material is under the same copyright protections as the article itself.

# RCode file
The code can be run in R v4.5.2, and was used to conduct statistical analysis from the data files below.

# Data files
These are used for statistical analysis and figure generation in the RCode file.

## SCP.csv
This reports supercooling point (SCP) for beetles during a gradual cooling protocol. Beetles were kept at 4C for 1 week prior to the SCP measurements. Each row pertains to a different individual, with information provided for each variable (column heading), as described below. 

VARIABLE: DESCRIPTION<br>
#Beetle ID: Unique beetle identifier<br>
#Mass: Weight of the beetle in grams<br>
#Sex:Whether the beetle was male (M) or female (F)<br>
#SCP: Supercooling point (SCP) in degrees Celcius, the temperature at which internal ice formation begins
#Alive: Whether the stonefly was alive (Yes) or not (No) following thawing<br>

## InoculativeFreezing.csv
This summarizes the number of beetles that were frozen, chilled, handling controls, and whether they survived or did not after exposure to -3, -5, or -8C for 20 hours. The tempeature is recorded in the first row, and the count of beetles in each cateory is listed below the temperature.

## ProportionMated.csv
This summarizes the proportion of male beetles that mated within a 4-hour observation period 1-3 days following exposure to control conditions (4C) or chilled conditions (0C [Zero] or -4C [MinusFour]) for 4 hours. The observation day (1, 2 or 3) is indicated in the first row, and the proportion of beetles that mated following each exposure is listed below the day.

## LatencyAndCopulation4h ... or 8h.csv
This reports the time before a male initiated mating (latency) and duration of the copulation in minutes during a 4 h or 8 h observation period following exposure of that male to control conditions (4C) or chilled conditions (0C [Zero] or -4C [MinusFour]) for 4 hours. Each row pertains to a different individual, with information provided for each variable (column heading), as described below.

VARIABLE:DESCRIPTION<br>
#Male ID: Unique beetle identifier<br>
#Treatment: Whether the male beetle was kept at 4 degrees Celcius (control) or exposed to 0 degrees Celcius (Zero) or -4 degrees Celcius [MinusFour] for 4  hours prior to the mating observation<br>
#Froze: 0 if the beetle didn't freeze, 1 if the beetle did freeze during the temperature exposure<br>
#Petri Dish #: Unique identifier for the container the beetle was placed in for mating observations<br>
#Observation Day: Whether mating was observed 1, 2, or 3 days post-temperature exposure<br>
#Mated: 0 if the beetle didn't mate during the observation period (4 or 8 hours), 1 if the beetle did mate<br>
#Latency (min): time in minutes for the male to initiate mating<br>
#Copulation duration (min): time in minutes that the male maintained copulation with the female <br>
#Experiment duration (min): time in minutes of the observation period - 240 min (4 hours) or 480 (8 hours)<br>
