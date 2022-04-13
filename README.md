# HCDE410

#HCDE410SP22
Files for HCDE410SP22 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data


DESCRIPTION
This project's goal is to better learn about the process of exploring traffic patterns on the Burke Gilman trail, and asking and answering specific research questions using that data. The data comes from data.seattle.gov which is an online portal where the city of Seattle hosts publicly-available datasets.

The notebook uses the Burke Gilman trail north of NE 70th St Bicycle and Pedestrian Counter dataset, which collects north and south traffic by bicyclists and pedestrians on a high-traffic portion of the Burke Gilman trail, the data used in this excersise only one years worth, 2019.

LISCENCE AND SOURCE DATA
The license of this data is "Public Domain" to learn more access the data source here: https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bicycle-and/2z5v-ecg8. In this source you can view the data itself, details about its creation and ownership as well as ways to visualize, export, share and access via API.

The Seattle Open Data Terms of Use and Privacy: https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/ can provide more details regarding how the data is controlled and the City of Seattle's Privacy policy. 

API DOCUMENTATION
The API documentation for the Burke Gilman trail north of NE 70th St Bicycle and Pedestrian Counter dataset can be found here: https://dev.socrata.com/foundry/data.seattle.gov/2z5v-ecg8

FIELDS IN FINAL DATA
The fields in this data set are:
hour of the day - The date and hour of day object(s) are detected by the sensor. Follows the 24 hour clock 
northbound bikes (bikes_north) - The total number of bicyclists traveling north in one hour as recorded by the sensor.
southbound bikes (bikes_south) - The total number of bicyclists traveling south in one hour as recorded by the sensor.
northbound pedestrians (ped_north)- The total number of pedestrians traveling north in one hour as recorded by the sensor.
southbound pedestrians (ped_south)- The total number of pedestrians traveling south in one hour as recorded by the sensor.

SPECIAL CONSIDERATIONS
The dataset was last updated April 22, 2022 (as of 4/12/22) and it refreshes monthly. It was created in 2014 and is owned by the Seattle Department of Transportation. The City of Seattle also reserves the right to discontinue any data collection at any time for any reason, so it may not be permenent. 
