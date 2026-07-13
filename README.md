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
#Sex: Whether the beetle was male (M) or female (F)<br>
#SCP: Supercooling point (SCP) in degrees Celcius, the temperature at which internal ice formation begins
#Alive: Whether the stonefly was alive (Yes) or not (No) following thawing<br>

## InoculativeFreezing.csv
This summarizes the number of beetles that were frozen, chilled, handling controls, and whether they survived or did not after exposure to -3, -5, or -8C for 20 hours. The tempeature is recorded in the first row, and the count of beetles in each cateory is listed below the temperature.

## InoculativeFreezingAll.csv
This contains the data used to generate the summary in InoculativeFreezing.csv, as well as Table 1 in the article. Each row contains one observation, with details in the columns as described below.

VARIABLE: DESCRIPTION<br>
#Sex: Whether the beetle was female (F) or male (M)<br>
#Beetle ID: Numerical identifier for beetles of a particular sex chilled (or handled) on a specific date<br>
#Mass of Beetle (grams): Mass of each beetle in grams<br>
#Date chilled: Date in DD-MMM-YY that beetles were exposed to the experimental conditions<br>
#Temp of chilling: Temperature in degrees Celcius that beetles were exposed to if frozen or chilled; handling controls associated with each temperature exposure also have the freezing/chilling temperature indicated even thought handling controls were kept at 4 degrees Celcius<br>
#Treatment: Whether ice was added (to inoculate freezing) or not (to allow beetles to remain unfrozen) or whether the beetles were handling controls maintained at 4 degrees Celcius<br>
#Papertowel exotherm: Y if the wet paper towel surrounding the beetle froze, N if not; N/A for handling controls<br>
#Beetle exotherm: Y if the beetle frozen, N if not; N/A for handling controls<br>
#Survival: Whether the beetle was alive (motilty) 48 hours after the end of the temperature exposure (Y - yes, N - no)<br>

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
#Latency (min): Time in minutes for the male to initiate mating<br>
#Copulation duration (min): Time in minutes that the male maintained copulation with the female <br>
#Experiment duration (min): Time in minutes of the observation period - 240 min (4 hours) or 480 (8 hours)<br>

## Cryoprotectants.csv
This includes the concentration of various putative cryoprotectants measured in fat body tissue from lady beetles that were maintained under control conditions (4C) or exposed to -3C in a frozen (Frozen) or unfrozen (Chilled) state for 20 hours, followed by 48 hours recovery at 4C. Cryoprotectants were determined by spectrophotometric assays as described in the article. Each row pertains to a different individual, with information provided for each variable (column heading), as described below.

VARIABLE:DESCRIPTION<br>
#SampleID: Unique beetle identifer<br>
#Treatment: Whether the beetle was maintained under control conditions (4C) or exposed to -3C in a frozen (Frozen) or unfrozen (Chilled) state prior to measuring cryoprotectant concentrations<br>
#Glycerol: Concentration in micromoles per gram of fat body tissue (wet mass) of glycerol<br>
#Inositol: Concentration in micromoles per gram of fat body tissue (wet mass) of myo-inositol<br>
#Proline: Concentration in micromoles per gram of fat body tissue (wet mass) of proline<br>
#Trehalose: Concentration in micromoles per gram of fat body tissue (wet mass) of trehalose<br>
