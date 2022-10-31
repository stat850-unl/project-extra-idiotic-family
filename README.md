---
output:
  pdf_document: default
  html_document: default
---
Stat 850 Project Description
================
Malith Premarathna, Pranta Das

## Instructions

Each member of your team should modify this document in some way and
push their modifications to the repository in a separate commit. This
will ensure that you have set your repository up in a way that ensures
all group members are working with the same repository.

Note that you must compile your readme (this document) for it to
properly display as part of your github repository.

Once you have received feedback on your project proposal (via Canvas)
you may alter this README so that it describes your final project
instead of the project proposal.

## Data Set
We are thinking about dealing with crime dataset. Here is the link of the data we are planning to used: https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

## Data set Description
This dataset reflects incidents of crime in the City of Los Angeles dating back to 2020. There are 521k rows (each row is a crime incident) and 28 columns (Variables).

1. *DR_NO* - Division of records number: Official file number made up of a 2 digit year, area ID, and 5 digits.

2. *Date Rptd* - Reported date of the crime

3. *Date OCC* - Occured date of the crime

4. *TIME OCC* - occured time of the crime in 24 hour military time.

5. *AREA* - The Los Angeles Police Department has 21 community police Stations referred to as Geographic Areas within the department. These Geographic Areas are sequentially numbered from 1-21. 

6. *AREA NAME* - Name designation of the area.

7. *Rpt Dist No* - A four digit code that represents a sub area with a geographic Area.

8. *Part 1-2* - no discription

9. *Crm cd* - indicates the crime committed (same as the *Crm cd 1*)

10. *Crm cd Desc* - Defines the crime Code Provided.

11. *Mocodes* - Activities associated with the suspect in commission of the crime.

12. *Vict Age* - Age of the Victim.

13. *Vict Sex* - Sex of the Victim (*F* - Female/ *M* - Male, *X*- Unknown)

14. *Vict Descent* - Descent Code of the Victim (*A*-other Asian, *B*-Black, *C*-Chinese, etc.)

15. *Premis Cd* - The type of structure, vehicle, or location where the crime took place.

16. *Premis Desc* Defines the Premis Cd provided.

17. *Weapon Used Cd* The type of weapon used in crime given as a code.

18. *Weapon Desc* Defines the code of the weapon used in crime.

19. *Status* Provides the status of the case in code.

20. *Status Desc* Description of the status code provided.

21. *Crm Cd 1* It indicates the crime committed where Crime Code 1 represents the most serious crime. 

22. *Crm Cd 2* It also indicates the crime code but it is less serious than Crm Cd 1.

23. *Crm Cd 3* This crime code is for less serious crime than represented by Crm Cd 1 and Crm Cd 2.

24. *Crm Cd 4* This crime code is for the least serious crime.

25. *LOCATION* Street address of crime incident rounded to nearest hundred blocks.

26. *Cross Street* Cross street of the rounded address.

27. *LAT* Latitude.

28. *LON* Longitude.



## Potential Topics to Explore Using the Data Set

We will explore following facts using the data.

1. Which area has the highest number of crimes among the 21 Police Stations.

2. Create a table for area and the sub area to identify the most awful sub area.

3. Use *Crm cd* and *Crm cd* data to explore Which is the most frequent crime type.

4. Present a Side by side box plot for the ages with most frequent 5 types of  crime in order to identify whether there is a targeted age for particular crime. 

5. Bar plot of crime type (crm cd) filled with victim sex, descent in order to identify whether there is a targeted sex, descent for particular crime.

6. Creating a word cloud about premises for frequently occurred crimes.

7. Explore whether the commiter has used different weapons for commiting the same crime for male's and female's.

8. Identify which types of crimes are getting resolved and which type of crimes are not getting resolved based on the status(Current) of the case.

9. We will try to plot a map to explore which area has the highest number of crimes using the Latitude and Longitude variables in the data set. This is a same exploration we suggested in 1 but this is also in mind. We will try to present either one of them.


## Group Members

1. Malith Premarathna
2. Pranta Das
