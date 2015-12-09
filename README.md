# Writing-about-your-data
The data I am using in this series of Coursera classes is from the National Epidemiologic Survey on Alcohol and Related Conditions, Wave I, run by the National Institute on Alcohol Abuse and Alcoholism (NIAAA, part of the National Institutes of Health, or NIH).  This wave of data was collected in 2001-2002 and includes questions to be able to assess five mood disorders, four anxiety disorders, and seven personality disorders, based on their classification in the American Psychiatric Association’s Diagnostic and Statistical Manual of Mental Disorders, Fourth Edition (DSM-IV).  The survey also includes questions on alcohol use, tobacco use, use of other medications and drugs, family history of drug use, family history of depression, family history of personality disorders, gambling, and medical conditions.  

Procedure
The purpose of the NESARC survey was to be the largest comorbidity study conducted to look at comorbidity between alcohol use and disorders and other issues, such as mental illness.  The survey sample (N=43,093) includes the civilian, non-institutionalized adult population of the United States, and was conducted at the individual level.  The sample is representative of US adults.  Data were collected in face-to-face, computer-assisted interviews conducted in respondents’ homes.  The response rate is 81%.  More information about NESARC can be found here: http://pubs.niaaa.nih.gov/publications/arh29-2/74-78.htm

Measures
My research interest is investigating characteristics associated with depression, specifically stresses experienced as well as sex and class differences.  My model uses stressors as the explanatory variable, depression as the response variable, and sex and income as potential moderating variables.  The depression variable (MAJORDEP12) asks whether respondents have experienced major depression in the past 12 months, with responses being 0 (No) or 1 (Yes).  Sex includes response options “male” (1) and “female” (2).  For ease of analysis and interpretation, sex was recoded to 0 (male) and 1 (female).  For class, I am using the raw income variable “Total personal income in last 12 months,” represented as a number between 0 and 3,000,000.
The stressors included are:
- “Any family members or close friends died in the last 12 months?”
- “Any family members or close friends had serious illness or injury in the last 12 months?”
- “Moved/anyone new came to live with you in last 12 months?”
- “Fired or laid off from job in last 12 months?”
- “Unemployed and looking for work for >1 month in last 12 months?”
- “Had trouble with boss or coworker in last 12 months?”
- “Changed jobs, job responsibilities, or work hours in the last 12 months?”
- “Got separated or divorced or broke off steady relationship in last 12 months?”
- “Had problems with neighbor, friend or relative in last 12 months?”
- “Experienced major financial crisis, bankruptcy or been unable to pay bills on time in last 12 months?”
- “You or family member had trouble with police, got arrested or sent to jail in last 12 months?”
- “You or family member been victim of crime in last 12 months?”
Each of these variables were originally coded as 1 (Yes), 2 (No), and 9 (Unknown), but I have recoded them as 0 (No) and 1 (Yes).  The aggregated variable makes a sum of the “yes” responses to these questions.  In previous analyses, this aggregated variable has been associated with experiencing depression.     





Assignment 1: Writing About Your Data
RECAP My research question:
I am interested in the question if there are any spatial patterns in the distribution or in the morphology of craters on the Martian surface.
Step 2: Describe the procedures that were used to collect the data.
a) Report the study design that generated that data (for example: data reporting, surveys, observation, experiment).
The study is an observational study.
b) Describe the original purpose of the data collection.
Understanding crater populations is a key part of understanding the history of the solar system. From the initial collisions that formed the planets to the continued impacts today, knowing the impactor population and flux through time is integral to interpreting the geologic past and its processes. Because crater sizes relate to the object that formed them, comprehensive studies of crater populations inform impactor population censuses. Craters can be used to determine relative surface ages, resurfacing rates, and properties of the crust within which they form. Differences in impact crater morphology from an expected norm can be used to glean further information about the surface and near-surface properties that modified them. Craters are vital to understanding planetary crustal properties as well as surface ages and modification events. They allow inferences into the ancient climate and hydrologic history, and they add a key data point for the understanding of impact physics.
c) Describe how the data were collected.
The bulk of crater identification and classification was done using THermal EMission Imaging System (THEMIS) mosaics. In ArcGIS software, THEMIS Daytime IR mosaics were used to manually locate all visible craters with diameters D>1 km in approximate local coordinate systems. Crater identification was accomplished using ArcGIS’s editing tools to draw a polyline that traced the visible rim of each crater. After crater identification and fitting, Mars Orbiter Laser Altimeter (MOLA) gridded topographic data was used to derive relevant topographic information for each D>3 km crater. The height of the rim, elevation of the surrounding surface, and greatest depth of the crater cavity were recorded. This was done in Igor Pro software using custom-built algorithms.
d) Report when the data were collected.
The data was collected by Stuart James Robbins for his PhD thesis. The Thesis was submitted in 2011. Based on the date of submission of his Master Thesis in 2008, it appears that the dataset was generated between 2008 and 2011.
e) Report where the data were collected.
The thesis by Stuart James Robbins was submitted to the Faculty of the Graduate School of the University of Colorado, Department of Astrophysical and Planetary Sciences. Thus, it seems that the data was collected in an office room, in fornt of a computer, somewhere in Boulder, Colorado, in the USA.
References
Robbins, S. J., & Hynek, B. M. (2012). A new global database of Mars impact craters≥ 1 km: 1. Database creation, properties, and parameters. Journal of Geophysical Research: Planets (1991–2012), 117(E5).







Assignment 1: Writing About Your Data
RECAP My research question:
I am interested in the question if there are any spatial patterns in the distribution or in the morphology of craters on the Martian surface. For example, one specific research question is, whether there is a difference in crater counts between the northern and the southern hemispheres. Another specific research question I want to investigate is, whether there is a difference in crater morphologies among longitudinal sectors of the Martian surface.
Step 3: Describe your variables.
a) Describe what your explanatory and response variables measured.
For the first mentioned research question above the explanatory variables are the ‘northern’ and the 'southern hemisphere’, and the response variables are the number of crater counts. More generalized, the explanatory variable is a spatial domain, either hemispheres, longitudinal or latitudinal sectors, etc. The response variables are either the number of craters, the mean/max/min of crater diameters, the mean/max/min depth or the number of lobes surrounding the crater rims, among others, within the spatial domain.
b) Describe the response scales for your explanatory and response variables.
In general the spatial domain (explanatory variable) is a categorical variable e.g. 'northern’ and 'southern’. In contrast the response variable may be a categorical (e.g. morphological structure) or a numeric (e.g. mean/max/min diameter of craters within a spatial domain) variable.
c) Describe how you managed your explanatory and response variables.
The spatial domains are subsets of the original datasets based on logical statements. E.g. the northern hemisphere corresponds to all items of the data for which the latitude > 0, whereas the southern hemisphere corresponds to all items of the data for which the latitude < 0. In many cases the response variables are not managed at all; however, in cases when the crater attributes are numeric (e.g. crater diameter), the numeric variables are transformed in a categorical variable (e.g. small, mean and large crater diameter).
