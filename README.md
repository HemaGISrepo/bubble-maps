# bubble-maps

A bubble map uses circles instead of markers. By varying the size and color of each circle, we can also show the relationship between location and two other variables.

We create a bubble map by using folium.Circle() to iteratively add circles. In the code cell below, robberies that occurred in hours 9-12 are plotted in green, whereas robberies from hours 13-17 are plotted in red.

Output:

![image](https://user-images.githubusercontent.com/118595650/202857037-c0e06e6d-5729-4160-85a4-12340984087e.png)



Note that folium.Circle() takes several arguments:

location is a list containing the center of the circle, in latitude and longitude.
radius sets the radius of the circle.
Note that in a traditional bubble map, the radius of each circle is allowed to vary. We can implement this by defining a function similar to the color_producer() function that is used to vary the color of each circle.
color sets the color of each circle.
The color_producer() function is used to visualize the effect of the hour on robbery location.
