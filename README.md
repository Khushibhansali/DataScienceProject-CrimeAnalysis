**Crime Analysis: DC, Maryland, Virginia
**


The arrest table dataframe contains 63,892 entries, recording details such as gender, location, neighborhood, crime offense, and more. For this analysis, I focused on the first thousand entries to examine the distribution of specific crimes by gender. The offenses analyzed include narcotics, common assault, recovered property, and others. The map visualization uses the following color scheme:

Light gray: Other - Male
Black: Other - Female
Light green: Narcotics - Male
Dark green: Narcotics - Female
Blue: Common Assault - Male
Dark blue: Common Assault - Female
Purple: Recovered Property - Male
Pink: Recovered Property - Female
The selected fields ('incidentOffense', 'lat', 'long', 'sex') allowed me to determine the occurrence of these crimes across Maryland, Virginia, and DC by gender. By limiting the sample to the first 1000 entries, the goal was to assess how representative this sample is of the overall dataset.

The resulting map shows that light green (Narcotics - Male) and blue (Common Assault - Male) are the most prominent colors, indicating that these offenses are the most frequent among males in the sample. This observation aligns with the overall trends in the larger dataset, where 87-Narcotics and 4E-Common Assault are the most common offenses. Thus, the sample is indeed representative of the population.

