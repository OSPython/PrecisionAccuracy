# PrecisionAccuracy
Graphically demonstrate meaning of precision and accuracy

When measuring something, the concepts of precision and accuracy are critical:

- Accuracy refers to how close the measurements are to the true value.
- Precision refers to how close the measurements are to each other.

Below, I demonstrate the the following possibilities:

1. High accuracy, High precision
2. Low accuracy, High precision
3. High accuracy, Low precision
4. Low accuracy, Low precision

For each of these sets, I've provided two subplots: 
1. Scatter plot of the data
2. Histogram plot showing the distribution of the measurements

The use of both scatter and histogram plots help visualize the difference between accuracy and precision. For high precision data, regardless of accuracy, the data points are closely packed together. For low precision, the data points are spread out. Accuracy is visualized by how close the data points are to the true value (the black dashed line). If they're generally close to the line, they're more accurate. If they're farther from the line, they're less accurate.

The plots shown below along with generating the synthetic data were all done using Python.
The matplotlib library was used to create these plots. The function plt.subplots was used to create the figure and a grid of subplots. hlines is used to plot horizontal reference lines for better visual perception of the accuracy. The scatter function plots the data points of measurements over time points and the hist function plots a histogram. The xlim, ylim, xlabel, ylabel, and title functions are used to set the properties of the plots. 

Colors and differing titles are used for clearer distinction between the subplots. The tight_layout function adjusts subplot params so that the subplots fit in to the figure area. Finally, plt.show() displays all the figures and blocks until the figures have been closed.

This code serves as a good, quick visualization to understand the possibilities of accuracy and precision in experiment measurements.
