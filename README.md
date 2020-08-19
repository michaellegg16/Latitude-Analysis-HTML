# **Latitude-Analysis-HTML**

### Task

* Create a visualization dashboard website using visualizations of latitudinal weather data.
* Create individual pages for each visualization that can be accessed from a dropdown menu.
* Design a landing page where a comparison of each plot can be seen.
* Design a data page where the data used to build the plots can be viewed.

* ["Landing" page](#landing-page):
  * Include an explanation of the project.
  * Include links to each visualizations page.
  
  ![landing](https://github.com/michaellegg16/Web-Design-Challenge/blob/master/Screenshots/LandingPage.png)
  
* ["Visualization" pages](#visualization-pages):
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
  
  ![visualization](https://github.com/michaellegg16/Web-Design-Challenge/blob/master/Screenshots/MaxTempPage.png)
  
* ["Comparisons" page](#comparisons-page):
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
  
    ![comparisons](https://github.com/michaellegg16/Web-Design-Challenge/blob/master/Screenshots/ComparisonsPage.png)

* ["Data" page](#data-page):
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Use the pandas function "to-HTML"!
    
  ![data](https://github.com/michaellegg16/Web-Design-Challenge/blob/master/Screenshots/DataPage.png)


### Instructions

1. If desired, the data can be viewed/analyzed using the Jupyter Notebook file.
1. Run the HTML with a local live sever (for testing) or simply go to the website deployed at, , to see the dashboard.
1. Use the "inspect" tool (Ctrl + alt + I) to view the HTML if desired.


### Conclusion

The actual conlcusions from the visualizations are as expected. Temperature goes down as latitude increases and vice-versa. Humidity, cloudiness, and wind speed are much less correlated to latitude, although wind speed does increase somewhat dramatically towards the highest latitudes. In the end, this project was for instructive purposes only, so that data itself is somewhat irrelevant. Personally, this was my first exposure to HTML and it has left me with mixed feelings. I also suddenly have a newfound appreciation for websites with sophisticed user interfaces. While I did find HTML to be a bit tedious, I certainly understand the need for it. This was only a glimpse into the true power of HTML/CSS and I have now designed my first visualization dashboard website!
