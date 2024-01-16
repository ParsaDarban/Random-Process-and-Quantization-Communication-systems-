# Random-Process-and-Quantization-Communication-systems

This exercise is dedicated to examining received signals in the presence of noise. We begin by introducing the Rayleigh distribution, which is a random variable. Understanding this distribution is crucial as the noises added to the signals are random.
In the following section, we analyze random processes and explore the necessary conditions for our process to be Wide Sense Stationary (WSS).
The concluding section introduces us to a digital communication system utilizing MPAM modulation, where we investigate its performance in the presence of noise.
PART1
As stated in the project description, if two independent normal random variables, x and y, with zero means and unit variances, are given, the Rayleigh distribution is obtained from the following relationship.

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/78d3c4c8-5343-4803-b062-8b2b95984b33)

Now, let's proceed to calculate its probability density function (pdf) and depict it as follows:

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/85fd9361-3a06-4e44-a3f6-5bdbeb9724f0)

Figure 1.1(PDF & CDF of Rayleigh distribution)

In this section, we generate independent normal variables, x and y, which lead to the creation of our Rayleigh variable. Using the "randn" command, we create these variables with a length of 103. This command generates variables with a mean close to zero and a variance close to one for us.

Now, let's display their histogram with a bin count of 100 (the number of bars plotted). The results are as follows:

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/89a1b191-d93c-4e47-a1e1-b7c927857652)

The mean of the random variable x: [Mean of x]

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/c4cf52e6-22f0-4038-8147-6bd3f9810826)

The mean of the random variable y: [Mean of y]

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/792536e0-0c54-44e6-a7b7-753d7fc71db4)

As observed, the mean and variance align with the specifications mentioned in the question.
