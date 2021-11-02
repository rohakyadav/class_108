Topic Bell Curve- the Normal Distribution

Class Description: t creates and plots different kinds of data to identify patterns in how data is distributed.

introduced to the normal distribution and its omni-presence in the nature.

Goal :

● plot data from random dice throws ● identifie the bell curve pattern in the data ● plot other kinds of data and identifies similar bell-curve patterns

● plot data from random dice throws ● identifie the bell curve pattern in the data ● plot other kinds of data and identifies similar bell-curve patterns

We can easily write code to generate another random number between 1 and 6 for dice 2

Python has a random module which helps generate random number. Let's generate one random number between 1 to 6 and store it in a variable called dice1. random.randint() can be used to generate random

 [number....you](https://number....you/)

 can pass the minimum number and maximum number between which you want to generate random values We can print the value.

Let us use plotly express to draw a histogram or bar graph for the data we have and see how the data is distributed.

writes code to draw a histogram for the data with x axis containing the dice rolls and y axis containing the count.

Let us run the code and look at how the distribution looks like. What do you see? There are more values in the centre. The higher values and lower values are less.

If you could join all the left edges of the bar graph, you would see that the distribution of numbers is almost like a bell-shape. This bell shape distribution is very common in nature. This is why it is called "normal distribution". Most of the different kinds of data in the universe follow this pattern. In fact, we expect different kinds of data to follow this pattern.



We can also draw a distribution plot directly using plotly's figure_factory module. We will need to additionally install scipy package on our system.

Remember, the heights and weights data for 18 year olds which we used in our earlier class. What would be the distribution of heights and weights in these 18 year olds ? Do you think they will follow a pattern?

The distribution might be a bell curve There will be more 18 year olds having average height and less number of 18 year olds too short or too tall. x axis would be the weight / height. y axis would the the number of people having specific weights and heights

The normal distribution or bell curve pattern is universally present in nature. Most data distributions follow this pattern. In fact, we expect data to follow the normal distribution. We will be learning how this is a very important in statistical analysis. Knowing how data will be distributed also gives us a chance to predict what the new data could be. This will be very important in machine learning and AI algorithms. We will be learning amore about using normal data distributions in the coming classes.