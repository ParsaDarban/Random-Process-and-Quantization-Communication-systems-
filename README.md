# Random-Process-and-Quantization-Communication-systems
<span style="font-family: Times New Roman (Headings CS), sans-serif;">Your text here</span>
PART1

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
 
Figure 1.2(histogram of two normal distribution (N=1000))

The mean of the random variable x: [Mean of x]

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/c4cf52e6-22f0-4038-8147-6bd3f9810826)

The mean of the random variable y: [Mean of y]

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/792536e0-0c54-44e6-a7b7-753d7fc71db4)

As observed, the mean and variance align with the specifications mentioned in the question.

Here, using the available relationships, we generate z. First, we deal with its mean and variance. As can be seen, these numbers are consistent with the results obtained in part A. (Our assumed variance is almost equal to one.)

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/600e5938-9a39-4688-a924-50886d74f8eb)

The histogram plot is as follows. As we can see, its shape approximately resembles the PDF in the first section. However, if we increase its length, the shape will exactly resemble what we implement in the next section.

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/7e381c34-eed5-4d5a-9b0d-700a4cec6a92)

Figure 1.3(histogram of Rayleigh distribution(N=1000))

In this section, we set the length of the normal variables to be 10^5. As we can see, the mean and variance of all three variables have become closer to the expected values.

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/d81b73a0-6c88-41df-a317-b27e6fcd09f4) ![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/558c31b7-926b-465e-ab5f-843a64df063c) ![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/7f590d7e-8c59-4e42-8b7e-2f4030f94847)

As we can see, since our numbers were calculated with high precision, the histogram of them is more similar to the PDF plot.

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/ff421b4d-7ba3-44f2-9c55-12f2a65e1ff4)

Figure 1.4(histogram of two normal distribution(N=100000))

![image](https://github.com/ParsaDarban/Random-Process-and-Quantization-Communication-systems-/assets/155367890/fc20ebf6-69aa-4740-a95c-cf39069bf9d4)

Figure 1.5(histogram of Rayleigh distribution(N=100000))

As can be observed, with the increase in N, the mean and variance of the normal variable have become closer to zero and one, respectively. As a result, the Rayleigh distribution constructed from two normal variables has also approached the expected values. The resulting shape is also closer to their PDF.
