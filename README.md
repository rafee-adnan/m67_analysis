# m67_analysis
We used HDBSCAN to separate the members of m67 from the background stars. We can see the isolated members of m67 in the Spatial Distribution diagram. The points are very close together in the Vector Point Diagram which also suggests that the stars are indeed the members of the m67 cluster.

From the parallax distribution, we can see that the members of the m67 cluster have a sharp peak in their parallax distribution which indicates the distance from the earth can be well defined.

We generated isochrones from CMD 3.5 input form and observed which isochrone is the best fit for the Color Magnitude Diagram of m67. The value of metal fraction Z is 0.021 and log(age/yr) is 9.6 for the best-fit isochrone. So the actual value should be somewhere around these values. And the log(age/yr) suggests that the age of m67 is 3.98 billion years old which matches the confirmed result(webda and wikipedia).

For determining distance we plotted histogram for 1/parallax values of the stars and saw most of the stars are lying between 840 parsecs and 900 parsecs. The mean of the distances is 870.35 with a standard deviation of 61.58 parsecs. These results also match with the confirmed results(webda).

And we also did non-linear regression called spline regression using specifying degree 4 with 4 knots. The spline regression line is very close to the best-fit isochrone which again confirms the authenticity of the best-fit isochrone.


![Screenshot from 2022-01-07 23-17-08](https://user-images.githubusercontent.com/76589056/148581658-e9adb66c-8bf0-48ac-b694-1c0003e600d8.png)
![Screenshot from 2022-01-07 23-17-25](https://user-images.githubusercontent.com/76589056/148581933-352677f4-3127-4981-afff-c0994e46f280.png)
## colab runtime 
https://drive.google.com/file/d/1XHqc-JgM9nb9Lz0ncIqBxku0Aa0WnyyO/view?usp=sharing
