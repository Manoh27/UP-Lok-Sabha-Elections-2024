# UP-Lok-Sabha-Elections-2024
A Power BI Report on 2024 Lok Sabha Election Results for the State of Uttar Pradesh.

Please find below details about my work,notaable features and references

**Datasets**
I have obtained the datasets from Wikipedia. Apart from the results, I have also considred different factors like Voter Turnout (in %), Turnout Drop/Increase (in %) compared to the prevous election and Winning margin (by votes polled) for every constituency in this Report.

**ETL Process**
ETL Processes involved in this project is of 2 steps. In the first step, URL of the website(wikipedia) is copied and pasted in Excel for extraction of Tabular data. There are different tabular data available in the web page. Required formatting and transformations have been done to make the data clean and then the file was saved. In the second step, the excel file that was saved was extracted into Power query, for conditional formatting. No DAX Queries were used for Conditional formatting.

**Map Visuals**
Power BI, doesn't have inbuilt maps containing boundaries of Indian Lok Sabha Contituencies. However it does support custom maps in topoJSON format. I got GIS Shape files from Bielefeld University website. You'll find map dumps in shp,dbf and shx formats. All you're supposed to do is combine those file formats in Map Shaper to have them in topoJSON format. To identify and 
avoid empty spaces, check whether the place names in your dataset and maps are same or not. This work is meant for educational/learning purpose, hence I'm using the data under fair use policy.

**Custom Tooltips**
Power BI does support custom tooltips, allows you to use any amount of details from the data that you want to show it in your visual as a tooltip, choose your background colour, fornt colour, font size etc. So I have implemented it in my work.

**Custom Legions**
Conditional formatting using field values containing color codes was done to obtained Customised legions. I have used tables to create customized legions. Colour codes for different datasets in different visuals were chosen an saved initially in Power query using conditional formatting. This data is obtained in Power BI in the form of a table. The properties of the table obtained as a visual, like Background color, font color were conditionally formatted using field values, containing colour codes.

**References**
Map Visuals - Bielefeld University
MapShaper and Custom Tooltips - oneaffidavit1 (Reddit)
Custom Legions - Enterprise DNA (Youtube Channel)
