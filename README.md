# NYC-Daily-Inmates-in-Custody(1991-2020)
A tableau visualization for the Custody of Inmates in NYC
# Introduction
New York has the highest number of inmates who are in custody, and its crucial to know about their mental health, which can be explained well with the help of few visualizations. 
This project is based on NYC Daily Inmates in Custody from 1991-2000. 
The dataset provided by the Department of Correction that falls into the Public Safety category and taken from the NYC Open Data. 
This dataset has daily update frequency, so there may be some inconsistencies with the number of rows and the number of columns in the dataset. 
There are 4143 observations and 13 columns in the dataset. 

# Data Dictionary

| Column Name | Description | Data Type | Expected Value |
|------------ |------------ | -----------| ------------- |
| Inmateid| A primary key that uniquely identifies each inmate record.| Number| |
| Admitted_Dt| Admitted date and time of the incident| Date & Time| |
| Custody_level | Level of custody provided for the inmate. | String (Plain Text) | MIN, MED, and MAX|
| Bradh| Whether the inmate is under mental observation or not.| String (Plain Text) | YES or NO|
| Race | Tells us the Race of the inmate| String (Plain Text) | A B, I, O, U and W|
| Gender| Gender of the inmate | String (Plain Text)| Male or Female|
| Age| Calculate the Age of the inmate | Number| |
| Inmate_Status_Code| Provides the inmate status example if the inmate is a detainee. | String (Plain Text) | CS= City Sentenced,CSP= City Sentenced - with VP Warrant,DE= Detainee, DEP= Detainee - with Open Case & VP Warrant, DNS= Detainee- Newly Sentenced to State Time
DPV= Detainee- Technical Parole Violator, SCO= State Prisoner- Court Order, SSR= State Ready |
| Infraction | Indicates whether the inmate has an infraction | String (Plain Text) | Yes or No|
