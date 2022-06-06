# PyBer Analysis   

# Overview of the analysis:  
Using pandas and Matplotlib we are tasked with determining how ride data differs by the type of city (Rural, Urban, Suburban).  We must create new dataframes, calculate sums and present a visulaization of our findings.

# Results:  
As we see in our summary dataframe (below):  
There are less Rural drivers, and less trips. The average fare is higher compared to other city types, however only a few of the drivers make up for the bulk of the rides, based on the low average of Fares per Driver, and the consdierably higher Average Fare per Ride.
In both urban and suburban markets, the rides are shorter and the number of drivers out-supply the demand; there are too many drivers, especially as we get more urban.  Further analysis is required to determine if this data represents only drivers that have taken a fare, or all drivers (active and inactive) within our network.  Another question to consider is if there was any driver turnover during this period, inaccurately increasing the number of drivers, even though their tenure never overlapped.  
![Summary Dataframe](https://user-images.githubusercontent.com/103051630/172215808-bc93575e-a587-46fc-9172-b0e15dbd6468.png)  

When we review the line chart (below), we see that there are a few peaks for for rural, but it is fairly consistent over the 4 month period.  As we move closer to urban, the fare data is a bit more volatile, particularly as move in to warmer months (May and beyond). Fares decrease sharply in the first week of May.  

![Total Fare by City Type and Date](https://user-images.githubusercontent.com/103051630/172215827-2bcc9657-7b8e-4f69-8ce0-685f82369277.png)


# Summary:  
Based on the results, my recommendations are as follows:  
1) Either increase ridership, or decrease the number of drivers across the board. Urban areas are the most in need, but even rural has too many drivers.
2) Offer incentives to ride during warmer months, including offering service to areas not typically serviced due to distance at a reduced rate( for example,  aheme park outside city limits at a flat rate, or the beach if you're a coastal city)

