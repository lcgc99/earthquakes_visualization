# earthquakes_visualization

The database used in this project was taken from public Tableau resources. It has 8313 logs from 1900 to 2013 taken from the USGS Earthquake Hazards Program of the US Geological Survey.

Each event has several characteristics which most important are: 
- Date.
- Geographic localization (longitude & latitude).
- Magnitude.
- Algorithm used to calculate the magnitude.

Those characteristics are plotted in the dashboard.

First, we have the date. I group logs by year resulting in the chart shown. We can see that logs arise in the last years. That would be interpreted in two main ways:
1. Before earthquakes were less often.
2. Last decades we could record more events thanks to technology.

Second, we have geographic localization. To show properly those data I used a geographic map with latitude and longitude bubbles. We can see that events occur mainly in the Ring of Fire, a region where there are plate tectonics collisions frequently.

Third, there is the magnitude. Due to the database has many magnitude values I decided to use a treemap. Data is in the Ritcher scale. As we can see 6 magnitude is the most frequent.

And finally, we have the algorithm used to calculate the magnitude shown in a pie chart. Each legend mean some specific calculation method which explanations can be consulted at https://www.usgs.gov/natural-hazards/earthquake-hazards/science/magnitude-types?qt-science_center_objects=0#qt-science_center_objects.

I added a time year filter which you can modify the temporal range. When you use it all charts change accordingly to date.

<p align="center">
  <img src="https://user-images.githubusercontent.com/81604875/120688691-edc9cb80-c468-11eb-8a6b-9f0401833af5.png"/>
</p>

To see and interact with the dasboard:
https://datastudio.google.com/reporting/f704b225-c0e3-4f60-b10e-72ca915ee0b1

