# Selg-Organizing-Maps

We need to design a Kohonen self organizing map (SOM), which gives as an output some shades of color mapped over 100 by 100 grid of neurones. The training input of the SOM are 24 colors (use shades of red, green, blue, with some yellow, teal and pink) which you can chose from the "RGB Color Table: Basic Colors" section of this page: http://www.rapidtables.com/web/color/RGB_Color.htm

Using a time varying learning rate πΆ(π) = πΆππππ(β π) where k is the current training epoch (starts with π» epoch 0), πΆπ = π. π , and T is the Total number of training epochs equal to 1000. Note that the epoch training involves all twenty four input samples for the 24 chosen colors to the network (hint: calibrate the color codes to values between 0 and 1, instead of being between 0 and 255). Initial weights are randomized.

The topological neighbourhood π΅π,π(π) of node (j) around the winning unit (i) is given by Where π!,"(π) = exp7β !," : 2π$(π) π(π) = π% exp ;β π= π π$ And π!," is the distance between the winning node i and surrounding node j.

# Problem

a) Generate a figure of the original grid (random weights) followed by figures of the SOM after 20, 40, 100, 1000 epochs. Change the value of π% = 1, 10, 30, 50, 70.

b) Draw your conclusions on how the output changes with π% and the number of epochs. Note: Basically, we need to have as the output of the SOM colors similar to: http://www.cs.hmc.edu/~kpang/nn/som.html (under βDemonstrationβ).
