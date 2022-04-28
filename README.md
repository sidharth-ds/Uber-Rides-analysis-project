# Uber-Rides-analysis-project
* Dataset contains september month Uber rides details of NewYork city.

### Dataset:
* It contains 4 features
   * Date-time, Latitude, Longitude
 
### Data preprocessing:
* Data cleaning
* creating new features (weekday, day, hour)

### Visualizations:(interpretations)
* By looking at the daily trips we can say that the Uber trips are rising on the "working days" and decreases on the "weekends".
* Uber trips according to the hours:
   * According to the hourly data, the Uber trips decreases after midnight and then start increasing after 5 am.
   * The trips keep rising till 6 pm such that 6 pm is the busiest hour for Uber then the trips start decreasing.
* Uber trips according to the weekdays:
   * on Sundays(0) the Uber trips are more than Saturdays(6)
   * so we can say people also use Uber for outings rather than for just going to work.
   * On Saturdays, the Uber trips are the lowest and on Mondays, they are the highest.
* Correlation of hours and weekdays on the Uber trips:
   * rides are maximum at around 6pm
   * minimum at around 1am to 3am
* As we are having the data about longitude and latitude so we can also plot the density of Uber trips according to the regions of the New York city:
   * rides are more concentrated within NYC.
