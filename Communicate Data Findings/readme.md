## Date created
15/7/2020

## Project Title
Ford GoBike System 

## Dataset

(Ford GoBike System Data)
#### This data set contains the following features:
>   
   - Trip Duration (seconds)
   - Start Time and Date
   - End Time and Date
   - Start Station ID
   - Start Station Name
   - Start Station Latitude
   - Start Station Longitude
   - End Station ID
   - End Station Name
   - End Station Latitude
   - End Station Longitude
   - Bike ID
   - User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

#### For cleaning i did the following:
> 1- change the data type for start and end time to be datetime64.
> 2- Fill null values with the mode.

#### for analysis i did the following:
> add new columns for trip duration in minute, trip start date in yyyy-mm-dd format, trip start hour of the day, day of week and month

## Summary of Findings:
>  
   - The Disturbution of duration in sec showing that almost all trips were under 3000 sec and the most of trips took time from 500 sec to 1000 sec which indices that riders uses the system in short time trip
   - The Disturbution of duration in min showing that almost all trips were under 1 hour which indices that riders uses the system in short time trip.
   - Most riders were Subscriber and a few of them were Customer.
   - Most riders didn't use bike share and a few of them use it.
   
   - The Most used Start Station is
   >   
       - Market St at 10th St                                   
       - San Francisco Caltrain Station 2  (Townsend St at 4th St)  
       - Berry St at 4th St                                          
       - Montgomery St BART Station (Market St at 2nd St)           
       - Powell St BART Station (Market St at 4th St)              
       - San Francisco Ferry Building (Harry Bridges Plaza)         
       - San Francisco Caltrain (Townsend St at 4th St)             
       - Powell St BART Station (Market St at 5th St)                 
       - Howard St at Beale St                                        
       - Steuart St at Market St
       
   - The Most used End Station is
      >   
       -  San Francisco Caltrain Station 2  (Townsend St at 4th St)                                   
       - Market St at 10th St 
       - Montgomery St BART Station (Market St at 2nd St)                                          
       - San Francisco Ferry Building (Harry Bridges Plaza)           
       - Powell St BART Station (Market St at 4th St)              
       - San Francisco Caltrain (Townsend St at 4th St)  
       - Berry St at 4th St               
       - The Embarcadero at Sansome St                  
       - Powell St BART Station (Market St at 5th St)                                 
       - Steuart St at Market St 
       
>       
   - The most used start time for clients were between 7 to 9 and 16 to 19 which mean that most of clients uses the bikes when they are going to the work or when they are back.
   - There was drop in the use of system in weekend and large use in work days which emphasis that clients use bikes for commuting.
   - All the rides happened in February because the data was collected only on that month
   - The higher percentage of customer rides longer trips then subscriber although number of subscriber riders are very high then customer.
   - The riding trips are much shorter on Monday through Friday compared to weekends. It indicates a pretty stable and efficient usage of the sharing system on normal work days, while more casual flexible use on weekends.
   - The trip distribution over day hours peaks around two timeframes, 2am to 3am and 13pm to 15pm.
   - The contrast between Customers and Subscribers. Customers have a relatively low usage of the bike share system with a small increase on the weekends. Subscribers are the opposite - there is steadily high usage on weekdays, with a sharp decline on the weekend
   - The number of subscribers usage are more than customers. There is a drop of volume on weekends for subscribers which indicates that they primarily ride bikes for work commute during work days, while almost the opposite pattern of a slight increase of use for customers on weekends demonstrates that the use was more for touring and relaxing purposes.
   - The Subsciber usually use bike for short time trip while Customer usually use it for long trip  and the common start time for Customer between 13 to 15.
   - Both the Subsciber and the Customer take the bikes in long trip on Saturday and Monday
   