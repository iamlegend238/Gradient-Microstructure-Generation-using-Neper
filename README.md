# Gradient-Microstructure-Generation-using-Neper
The process of generating synthetic microstructures is through distribution of seed points and their weights for obtaining a Voronoi tessellation. 
Manipulating this a code has been written in python to generate gradient microstructure so that we can obtain the coordinates of the seed points and weights. 
This seed points and weights can be the input files in Neper. 
From Neper documentation we can obtain the syntax for using this input files and then we generate a gradient microstructure that is useful in many areas of materials science (welding and so on).
We need to understand somethings from the code.
Our code is in python and it can be used for generation of 2D gradient microstructures ans 3D columnar gradient microstructures.
We have to enter how much grains we require as a first input in the code.
For the next input we input the ratio in which we want the grains / seeds in our case to be distributed.
Finally we input the ratio of the Area for which each ratio of the grains has to be distributed.
After this we get the Coordinates and Weights file as output.
Now we have to use syntax from the neper documentation for using this as input files to obtain gradient microstructures.
Thanks!
