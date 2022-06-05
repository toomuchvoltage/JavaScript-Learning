# Minimum Volume Object Oriented Bounding Box using Regression

This is a really simple way to do best fit OOBBs. It simply uses regression instead of principal component analysis.

# Here's how it works:

- First it computes the centroid and subtracts it from the data set. This is in preparation for finding the best fit plane.
- Then it regresses a spherical coordinate pair using gradient descent representing the best fit plane normal.
- Once the best fit plane is found, it then generates and rotates a pair of principal axis (again using regression/gradient descent) until a minimal volume bounding box is found.

# How to use

Simply open the .HTML file and hit refresh for new data points.

# Example

https://jsfiddle.net/5j4wmt6n/

![Example Run](https://raw.githubusercontent.com/toomuchvoltage/SINDyTestBed/master/BestFitOOBB-Regression/bestfitoobbexample.png)