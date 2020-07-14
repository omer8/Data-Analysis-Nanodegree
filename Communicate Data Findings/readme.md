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

#### Project Workflow:
> This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset Ford GoBike System Data. I used Python and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships. 
> In the second part, I took my main findings from my exploration and convey them to others through an explanatory analysis. To this end, I created a slide deck that leverages polished, explanatory visualizations to communicate my results.


## Summary of Findings:
>  
   - The average trip is just under 600 sec, with 90% of trips being under 2000 sec. Looking at the histogram, most rides fall in between the 50 - 2000 sec range. This suggests riders are taking the bikes short distances.
   - The 99% of the trips were less than 1 hour long with most of them fell between 5 to 15 minutes range.
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
   - The trip distribution over day hours peaks around two timeframes, 7am to 9am and 16pm to 18pm, during rush hours.
   - it is quite obvious that the majority of rides happened on work days (Mon-Fri) and primary usage is probably for commuting
   - All the rides happened in February because the data was collected only on that month
   - The higher percentage of customer rides longer trips then subscriber although number of subscriber riders are very high then customer.
   - The riding trips are much shorter on Monday through Friday compared to weekends. It indicates a pretty stable and efficient usage of the sharing system on normal work days, while more casual flexible use on weekends.
   - The trip distribution over day hours peaks around two timeframes, 2am to 3am and 13pm to 15pm.
   - The contrast between Customers and Subscribers. Customers have a relatively low usage of the bike share system with a small increase on the weekends. Subscribers are the opposite - there is steadily high usage on weekdays, with a sharp decline on the weekend
   - There was much more subscriber usage than casual customers overall. The drop of volume on weekends for subscribers indicates that they primarily ride bikes for work commute during work days, whereas almost the opposite pattern of a slight increase of use for customers on weekends demonstrates that the use was more for leisure/touring and relaxing purposes.
   - The Subsciber usually use bike for short time trip while Customer usually use it for long trip  and the common start time for Customer between 13 to 15.
   - Both the Subsciber and the Customer take the bikes in long trip on Saturday and Monday
   - The different usage between the two type of riders. Subscribers use the system heavily on work days i.e. Monday through Friday whereas customers ride a lot on weekends, especially in the afternoon. Many trips concentrated around 8-9am and 17-18pm on work days for subscribers when used for work commute, yet customers tend to use more in the late afternoon around 17pm Monday to Friday. Other than usage purpose and habit, it may also have to do with the traffic situation around these rush hours in the area.
