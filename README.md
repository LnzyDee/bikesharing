# Bike-sharing Challenge

## Bike-sharing Analysis Overview

The purpose of this analysis is, using the data from the NYC Citi Bike CSV, to make a bike-sharing proposal in Des Moines ideal for potential investors.

## Bike-sharing Results

### Tableau Story Link
See the full story at my Tableau Public page: [Bike-Share Challenge](https://public.tableau.com/views/bikeshare_challenge_16544009667730/BikeSharingStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### Checkout Times
![Checkout Times](/Images/tab_chk_times.png)
- The Checkout Times for Users worksheet shows that ride times are most often under an hour per use. As shown in the visualization the peak riding length is about 5 minutes.

### Checkout Times by Gender
![Checkout Times by Gender](/Images/tab_chk_gen_times.png)
- The Checkout Times by Gender worksheet shows the difference in the length of rides by gender. As seen above, male riders make up the majority of users, and as seen in the first slide, make up the majority of ride time at 5 minutes. Female riders also have the majority of rides around 6 minutes. The unknown users ride length is the highest at around 11 minutes.

### Trips by Weekday per Hour
![Trips by Weekday per Hour](/Images/tab_trp_wkdy_hr.png)
- The Trips by Weekday per Hour worksheet shows just as it says: the number of rides per hour for each weekday. As seen above, peak hours coincide with daily weekday work schedules; 7, 8 and 9 AM are darker, showing more use as would be expected. A tapering off is shown in the late morning and early afternoon hours with another peak at 5 and 6 PM, coinciding with the end of the workday. Weekends show more use in midday and the afternoon, as would be expected.

### Trips by Gender (Weekday per Hour)
![Trips by Gender Weekday per Hour](/Images/tab_trp_gen_wdhr.png)
- The Trips by Gender (Weekday per Hour) worksheet does the same as the Trips by Weekday per Hour, but splits users by gender. As can be gleaned from the gender checkout times sheet, males are the top users, followed by females and then unknown. The hours of use are similar as the Trips by Weekday per Hour sheet shows, with peak hours coinciding with the start and end of the workday.

### User Trips by Gender by Weekday
![User Trips by Gender by Weekday](/Images/tab_trp_gen_wkdy.png)
- The User Trips by Gender by Weekday worksheet separates the data by a few factors: Customer (general users) and Subscribers and then those are distinguished by gender. As expected, male users are more prominent, with male subscribers use peaking on Thursdays.
The same can be said of female and unknown users (more being subscribers and use peaking on Thursdays).

### August Peak Hours
![August Peak Hours](/Images/tab_aug_pkhr.png)
- The August Peak Hours worksheet displays the hours of the day with the total number of riders for those hours in the month of August. As the chart shows above, the busiest time for use is around 5 PM. This coincides, as stated above with the trips per hour sheet, with the typical end of the workday.

### Bike Usage
![Bike Usage](/Images/tab_bk_rpr.png)
- The Bike Usage worksheet shows which bikes are used most often (most used is shown in upper left, with the least used in the lower right). Using this data, we can find which bikes will most likely need checks or repairs.

## Bike-sharing Summary

- The results show that males make up the largest portion of users; a large number of those who do use the service are more likely to be subscribers, rather than general users; the highest use times are shown to be around the start and end of the typical workday.
- Two additional visualizations I would perform with the given dataset would be:
  - to find the most used start and end locations of each ride. This information would be helpful to find the best place to put bikes and maybe finding a place where there aren't any where they might be needed.
  - to find what age of users are more likely to try the service.

# Resources
- Data Source: [NYC Citi Bike Data (08-2019)](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip),
- Software: [Tableau Public](https://public.tableau.com/en-us/s/), [Python](https://www.python.org/), [Visual Studio Code](https://code.visualstudio.com/), 1.65.2