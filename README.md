# PACE_POINT
I originally created this database to calculate horse racing pace ratings based on a book named Modern Pace Handicapping written by Tom Brohamer. 
Over time it evolved to include ratings for many other aspects like speed, pedigree, and running styles.
This data is extracted from DRF past performace cvs files and imported into SQL Server as tables, 
from there it is transformed to match the data types required, and then inserted with calculations as needed.
It all takes off from there and you can follow along using the usp_start stored procedure.
Most stored procedures not listed in usp_start are accessed by the web application (to be included) for reporting purposes.
