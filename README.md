# machine-learning-exercise-1--linear-regression-and-gradient-descent-solved
**TO GET THIS SOLUTION VISIT:** [Machine Learning Exercise 1- Linear Regression and Gradient Descent Solved](https://www.ankitcodinghub.com/product/machine-learning-exercise-1-linear-regression-and-gradient-descent-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94656&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Machine Learning Exercise 1- Linear Regression and Gradient Descent Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Programming Exercise 1: Linear Regression

Machine Learning

Introduction

In this exercise, you will implement linear regression and get to see it work on data. Before starting on this programming exercise, we strongly recom- mend watching the video lectures and completing the review questions for the associated topics.

To get started with the exercise, you will need to download the starter code and unzip its contents to the directory where you wish to complete the exercise. If needed, use the cd command in Octave/MATLAB to change to this directory before starting this exercise.

You can also find instructions for installing Octave/MATLAB in the “En- vironment Setup Instructions” of the course website.

Files included in this exercise

ex1.m – Octave/MATLAB script that steps you through the exercise ex1 multi.m – Octave/MATLAB script for the later parts of the exercise ex1data1.txt – Dataset for linear regression with one variable ex1data2.txt – Dataset for linear regression with multiple variables submit.m – Submission script that sends your solutions to our servers [⋆] warmUpExercise.m – Simple example function in Octave/MATLAB [⋆] plotData.m – Function to display the dataset

[⋆] computeCost.m – Function to compute the cost of linear regression [⋆] gradientDescent.m – Function to run gradient descent

[†] computeCostMulti.m – Cost function for multiple variables

[†] gradientDescentMulti.m – Gradient descent for multiple variables [†] featureNormalize.m – Function to normalize features

[†] normalEqn.m – Function to compute the normal equations

⋆ indicates files you will need to complete † indicates optional exercises

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Throughout the exercise, you will be using the scripts ex1.m and ex1 multi.m. These scripts set up the dataset for the problems and make calls to functions that you will write. You do not need to modify either of them. You are only required to modify functions in other files, by following the instructions in this assignment.

For this programming exercise, you are only required to complete the first part of the exercise to implement linear regression with one variable. The second part of the exercise, which is optional, covers linear regression with multiple variables.

Where to get help

The exercises in this course use Octave1 or MATLAB, a high-level program- ming language well-suited for numerical computations. If you do not have Octave or MATLAB installed, please refer to the installation instructions in the “Environment Setup Instructions” of the course website.

At the Octave/MATLAB command line, typing help followed by a func- tion name displays documentation for a built-in function. For example, help plot will bring up help information for plotting. Further documentation for Octave functions can be found at the Octave documentation pages. MAT- LAB documentation can be found at the MATLAB documentation pages.

We also strongly encourage using the online Discussions to discuss ex- ercises with other students. However, do not look at any source code written by others or share your source code with others.

1 Simple Octave/MATLAB function

The first part of ex1.m gives you practice with Octave/MATLAB syntax and the homework submission process. In the file warmUpExercise.m, you will find the outline of an Octave/MATLAB function. Modify it to return a 5 x 5 identity matrix by filling in the following code:

A = eye(5);

1Octave is a free alternative to MATLAB. For the programming exercises, you are free to use either Octave or MATLAB.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
When you are finished, run ex1.m (assuming you are in the correct di- rectory, type “ex1” at the Octave/MATLAB prompt) and you should see output similar to the following:

<pre>              ans =
              Diagonal Matrix
</pre>
10000 01000 00100 00010 00001

Now ex1.m will pause until you press any key, and then will run the code for the next part of the assignment. If you wish to quit, typing ctrl-c will stop the program in the middle of its run.

1.1 Submitting Solutions

After completing a part of the exercise, you can submit your solutions for grading by typing submit at the Octave/MATLAB command line. The sub- mission script will prompt you for your login e-mail and submission token and ask you which files you want to submit. You can obtain a submission token from the web page for the assignment.

You should now submit your solutions.

You are allowed to submit your solutions multiple times, and we will take only the highest score into consideration.

2 Linear regression with one variable

In this part of this exercise, you will implement linear regression with one variable to predict profits for a food truck. Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet. The chain already has trucks in various cities and you have data for profits and populations from the cities.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
You would like to use this data to help you select which city to expand to next.

The file ex1data1.txt contains the dataset for our linear regression prob- lem. The first column is the population of a city and the second column is the profit of a food truck in that city. A negative value for profit indicates a loss.

The ex1.m script has already been set up to load this data for you. 2.1 Plotting the Data

Before starting on any task, it is often useful to understand the data by visualizing it. For this dataset, you can use a scatter plot to visualize the data, since it has only two properties to plot (profit and population). (Many other problems that you will encounter in real life are multi-dimensional and can’t be plotted on a 2-d plot.)

In ex1.m, the dataset is loaded from the data file into the variables X and y:

<pre>data = load('ex1data1.txt');       % read comma separated data
X = data(:, 1); y = data(:, 2);
m = length(y);                     % number of training examples
</pre>
Next, the script calls the plotData function to create a scatter plot of the data. Your job is to complete plotData.m to draw the plot; modify the file and fill in the following code:

plot(x, y, ‘rx’, ‘MarkerSize’, 10); % Plot the data ylabel(‘Profit in $10,000s’); % Set the y−axis label xlabel(‘Population of City in 10,000s’); % Set the x−axis label

Now, when you continue to run ex1.m, our end result should look like Figure 1, with the same red “x” markers and axis labels.

To learn more about the plot command, you can type help plot at the Octave/MATLAB command prompt or to search online for plotting doc- umentation. (To change the markers to red “x”, we used the option ‘rx’ together with the plot command, i.e., plot(..,[your options here],.., ‘rx’); )

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
25

20

15

10

5

0

−5

4 6 8 10 12 14 16 18 20 22 24

Population of City in 10,000s

Figure 1: Scatter plot of training data

2.2 Gradient Descent

In this part, you will fit the linear regression parameters θ to our dataset using gradient descent.

2.2.1 Update Equations

The objective of linear regression is to minimize the cost function

</div>
</div>
<div class="layoutArea">
<div class="column">
m

J(θ)= 1 􏰉􏰀hθ(x(i))−y(i)􏰁2

</div>
</div>
<div class="layoutArea">
<div class="column">
2m i=1

where the hypothesis hθ(x) is given by the linear model

</div>
</div>
<div class="layoutArea">
<div class="column">
hθ(x)=θTx=θ0 +θ1×1

Recall that the parameters of your model are the θj values. These are the values you will adjust to minimize cost J(θ). One way to do this is to use the batch gradient descent algorithm. In batch gradient descent, each iteration performs the update

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Profit in $10,000s

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
1 􏰉m

θj := θj − α (hθ(x(i)) − y(i))x(i) (simultaneously update θj for all j).

</div>
</div>
<div class="layoutArea">
<div class="column">
mj i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
With each step of gradient descent, your parameters θj come closer to the optimal values that will achieve the lowest cost J(θ).

2.2.2 Implementation

In ex1.m, we have already set up the data for linear regression. In the following lines, we add another dimension to our data to accommodate the θ0 intercept term. We also initialize the initial parameters to 0 and the learning rate alpha to 0.01.

<pre>X = [ones(m, 1), data(:,1)]; % Add a column of ones to x
theta = zeros(2, 1); % initialize fitting parameters
</pre>
<pre>iterations = 1500;
alpha = 0.01;
</pre>
2.2.3 Computing the cost J(θ)

As you perform gradient descent to learn minimize the cost function J(θ), it is helpful to monitor the convergence by computing the cost. In this section, you will implement a function to calculate J(θ) so you can check the convergence of your gradient descent implementation.

Your next task is to complete the code in the file computeCost.m, which is a function that computes J(θ). As you are doing this, remember that the variables X and y are not scalar values, but matrices whose rows represent the examples from the training set.

Once you have completed the function, the next step in ex1.m will run computeCost once using θ initialized to zeros, and you will see the cost printed to the screen.

You should expect to see a cost of 32.07. You should now submit your solutions.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Implementation Note: We store each example as a row in the the X matrix in Octave/MATLAB. To take into account the intercept term (θ0), we add an additional first column to X and set it to all ones. This allows us to treat θ0 as simply another ‘feature’.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
2.2.4 Gradient descent

Next, you will implement gradient descent in the file gradientDescent.m. The loop structure has been written for you, and you only need to supply the updates to θ within each iteration.

As you program, make sure you understand what you are trying to opti- mize and what is being updated. Keep in mind that the cost J(θ) is parame- terized by the vector θ, not X and y. That is, we minimize the value of J(θ) by changing the values of the vector θ, not by changing X or y. Refer to the equations in this handout and to the video lectures if you are uncertain.

A good way to verify that gradient descent is working correctly is to look at the value of J(θ) and check that it is decreasing with each step. The starter code for gradientDescent.m calls computeCost on every iteration and prints the cost. Assuming you have implemented gradient descent and computeCost correctly, your value of J(θ) should never increase, and should converge to a steady value by the end of the algorithm.

After you are finished, ex1.m will use your final parameters to plot the linear fit. The result should look something like Figure 2:

Your final values for θ will also be used to make predictions on profits in areas of 35,000 and 70,000 people. Note the way that the following lines in ex1.m uses matrix multiplication, rather than explicit summation or loop- ing, to calculate the predictions. This is an example of code vectorization in Octave/MATLAB.

You should now submit your solutions.

<pre>predict1 = [1, 3.5] * theta;
predict2 = [1, 7] * theta;
</pre>
2.3 Debugging

Here are some things to keep in mind as you implement gradient descent:

<ul>
<li>Octave/MATLAB array indices start from one, not zero. If you’re stor- ing θ0 and θ1 in a vector called theta, the values will be theta(1) and theta(2).</li>
<li>If you are seeing many errors at runtime, inspect your matrix operations to make sure that you’re adding and multiplying matrices of compat- ible dimensions. Printing the dimensions of variables with the size command will help you debug.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
25

20

15

10

5

0

−5

4 6 8 10 12 14 16 18 20 22 24

Population of City in 10,000s

Figure 2: Training data with linear regression fit

• By default, Octave/MATLAB interprets math operators to be matrix operators. This is a common source of size incompatibility errors. If you don’t want matrix multiplication, you need to add the “dot” notation to specify this to Octave/MATLAB. For example, A*B does a matrix multiply, while A.*B does an element-wise multiplication.

2.4 Visualizing J(θ)

To understand the cost function J(θ) better, you will now plot the cost over a 2-dimensional grid of θ0 and θ1 values. You will not need to code anything new for this part, but you should understand how the code you have written already is creating these images.

In the next step of ex1.m, there is code set up to calculate J(θ) over a grid of values using the computeCost function that you wrote.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Training data

Linear regression

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Profit in $10,000s

</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="layoutArea">
<div class="column">
% initialize J vals to a matrix of 0’s

J vals = zeros(length(theta0 vals), length(theta1 vals));

% Fill out J vals

for i = 1:length(theta0 vals)

for j = 1:length(theta1 vals)

t = [theta0 vals(i); theta1 vals(j)];

J vals(i,j) = computeCost(x, y, t);

end end

After these lines are executed, you will have a 2-D array of J(θ) values. The script ex1.m will then use these values to produce surface and contour plots of J(θ) using the surf and contour commands. The plots should look something like Figure 3:

</div>
</div>
<div class="layoutArea">
<div class="column">
800 700 600 500 400 300 200 100

0 4

</div>
<div class="column">
4 3.5 3 2.5 2 1.5 1 0.5 0 −0.5

</div>
</div>
<div class="layoutArea">
<div class="column">
3

2

</div>
<div class="column">
10

</div>
</div>
<div class="layoutArea">
<div class="column">
θ

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
<div class="column">
0

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
<div class="layoutArea">
<div class="column">
0 −5 −1

−10 −8 −6 −4 −2 0 2 4 6 8 10

</div>
</div>
<div class="layoutArea">
<div class="column">
−1 −10 θ 1θ0

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) Surface

</div>
<div class="column">
(b) Contour, showing minimum

</div>
</div>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: Cost function J(θ)

</div>
</div>
<div class="layoutArea">
<div class="column">
The purpose of these graphs is to show you that how J(θ) varies with changes in θ0 and θ1. The cost function J(θ) is bowl-shaped and has a global mininum. (This is easier to see in the contour plot than in the 3D surface plot). This minimum is the optimal point for θ0 and θ1, and each step of gradient descent moves closer to this point.

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
θ

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Optional Exercises

If you have successfully completed the material above, congratulations! You now understand linear regression and should able to start using it on your own datasets.

For the rest of this programming exercise, we have included the following optional exercises. These exercises will help you gain a deeper understanding of the material, and if you are able to do so, we encourage you to complete them as well.

3 Linear regression with multiple variables

In this part, you will implement linear regression with multiple variables to predict the prices of houses. Suppose you are selling your house and you want to know what a good market price would be. One way to do this is to first collect information on recent houses sold and make a model of housing prices.

The file ex1data2.txt contains a training set of housing prices in Port- land, Oregon. The first column is the size of the house (in square feet), the second column is the number of bedrooms, and the third column is the price of the house.

The ex1 multi.m script has been set up to help you step through this exercise.

3.1 Feature Normalization

The ex1 multi.m script will start by loading and displaying some values from this dataset. By looking at the values, note that house sizes are about 1000 times the number of bedrooms. When features differ by orders of mag- nitude, first performing feature scaling can make gradient descent converge much more quickly.

Your task here is to complete the code in featureNormalize.m to

• Subtract the mean value of each feature from the dataset.

• After subtracting the mean, additionally scale (divide) the feature values by their respective “standard deviations.”

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
The standard deviation is a way of measuring how much variation there is in the range of values of a particular feature (most data points will lie within ±2 standard deviations of the mean); this is an alternative to taking the range of values (max-min). In Octave/MATLAB, you can use the “std” function to compute the standard deviation. For example, inside featureNormalize.m, the quantity X(:,1) contains all the values of x1 (house sizes) in the training set, so std(X(:,1)) computes the standard deviation of the house sizes. At the time that featureNormalize.m is called, the extra column of 1’s corresponding to x0 = 1 has not yet been added to X (see ex1 multi.m for details).

You will do this for all the features and your code should work with datasets of all sizes (any number of features / examples). Note that each column of the matrix X corresponds to one feature.

You should now submit your solutions.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Implementation Note: When normalizing the features, it is important to store the values used for normalization – the mean value and the stan- dard deviation used for the computations. After learning the parameters from the model, we often want to predict the prices of houses we have not seen before. Given a new x value (living room area and number of bed- rooms), we must first normalize x using the mean and standard deviation that we had previously computed from the training set.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.2 Gradient Descent

Previously, you implemented gradient descent on a univariate regression problem. The only difference now is that there is one more feature in the matrix X. The hypothesis function and the batch gradient descent update rule remain unchanged.

You should complete the code in computeCostMulti.m and gradientDescentMulti.m to implement the cost function and gradient descent for linear regression with

multiple variables. If your code in the previous part (single variable) already

supports multiple variables, you can use it here too.

Make sure your code supports any number of features and is well-vectorized. You can use ‘size(X, 2)’ to find out how many features are present in the dataset.

You should now submit your solutions.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="section">
<div class="layoutArea">
<div class="column">
Implementation Note: In the multivariate case, the cost function can also be written in the following vectorized form:

</div>
</div>
<div class="layoutArea">
<div class="column">
where

</div>
</div>
<div class="layoutArea">
<div class="column">
J(θ)= 1 (Xθ−⃗y)T (Xθ−⃗y) 2m

</div>
</div>
<div class="layoutArea">
<div class="column">
 —(x(1))T —   —(x(2))T — 

</div>
<div class="column">
 y(1) 

 y(2)  ⃗y =   . .   .

</div>
</div>
<div class="layoutArea">
<div class="column">
X =   . .   ..

</div>
</div>
<div class="layoutArea">
<div class="column">
— (x(m))T — y(m)

</div>
</div>
<div class="layoutArea">
<div class="column">
The vectorized version is efficient when you’re working with numerical computing tools like Octave/MATLAB. If you are an expert with matrix operations, you can prove to yourself that the two forms are equivalent.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.2.1 Optional (ungraded) exercise: Selecting learning rates

In this part of the exercise, you will get to try out different learning rates for the dataset and find a learning rate that converges quickly. You can change the learning rate by modifying ex1 multi.m and changing the part of the code that sets the learning rate.

The next phase in ex1 multi.m will call your gradientDescent.m func- tion and run gradient descent for about 50 iterations at the chosen learning rate. The function should also return the history of J(θ) values in a vector J. After the last iteration, the ex1 multi.m script plots the J values against the number of the iterations.

If you picked a learning rate within a good range, your plot look similar Figure 4. If your graph looks very different, especially if your value of J(θ) increases or even blows up, adjust your learning rate and try again. We rec- ommend trying values of the learning rate α on a log-scale, at multiplicative steps of about 3 times the previous value (i.e., 0.3, 0.1, 0.03, 0.01 and so on). You may also want to adjust the number of iterations you are running if that will help you see the overall trend in the curve.

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
Figure 4: Convergence of gradient descent with an appropriate learning rate

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Implementation Note: If your learning rate is too large, J(θ) can di- verge and ‘blow up’, resulting in values which are too large for computer calculations. In these situations, Octave/MATLAB will tend to return NaNs. NaN stands for ‘not a number’ and is often caused by undefined operations that involve −∞ and +∞.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Octave/MATLAB Tip: To compare how different learning learning rates affect convergence, it’s helpful to plot J for several learning rates on the same figure. In Octave/MATLAB, this can be done by perform- ing gradient descent multiple times with a ‘hold on’ command between plots. Concretely, if you’ve tried three different values of alpha (you should probably try more values than this) and stored the costs in J1, J2 and J3, you can use the following commands to plot them on the same figure:

<pre>              plot(1:50, J1(1:50), ‘b’);
              hold on;
              plot(1:50, J2(1:50), ‘r’);
              plot(1:50, J3(1:50), ‘k’);
</pre>
The final arguments ‘b’, ‘r’, and ‘k’ specify different colors for the plots.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
13

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
Notice the changes in the convergence curves as the learning rate changes. With a small learning rate, you should find that gradient descent takes a very long time to converge to the optimal value. Conversely, with a large learning rate, gradient descent might not converge or might even diverge!

Using the best learning rate that you found, run the ex1 multi.m script to run gradient descent until convergence to find the final values of θ. Next, use this value of θ to predict the price of a house with 1650 square feet and 3 bedrooms. You will use value later to check your implementation of the normal equations. Don’t forget to normalize your features when you make this prediction!

You do not need to submit any solutions for these optional (ungraded) exercises.

3.3 Normal Equations

In the lecture videos, you learned that the closed-form solution to linear regression is

θ = 􏰀 X T X 􏰁 − 1 X T ⃗y .

Using this formula does not require any feature scaling, and you will get an exact solution in one calculation: there is no “loop until convergence” like in gradient descent.

Complete the code in normalEqn.m to use the formula above to calcu- late θ. Remember that while you don’t need to scale your features, we still need to add a column of 1’s to the X matrix to have an intercept term (θ0). The code in ex1.m will add the column of 1’s to X for you.

You should now submit your solutions.

Optional (ungraded) exercise: Now, once you have found θ using this method, use it to make a price prediction for a 1650-square-foot house with 3 bedrooms. You should find that gives the same predicted price as the value you obtained using the model fit with gradient descent (in Section 3.2.1).

</div>
</div>
<div class="layoutArea">
<div class="column">
14

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
Submission and Grading

After completing various parts of the assignment, be sure to use the submit function system to submit your solutions to our servers. The following is a breakdown of how each part of this exercise is scored.

</div>
</div>
<div class="layoutArea">
<div class="column">
Part

Warm up exercise

Compute cost for one variable Gradient descent for one variable Total Points

</div>
<div class="column">
Submitted File

<pre>warmUpExercise.m
computeCost.m
gradientDescent.m
</pre>
</div>
<div class="column">
Points

10 points 40 points 50 points 100 points

Points

0 points 0 points

0 points

0 points

</div>
</div>
<div class="layoutArea">
<div class="column">
Optional Exercises Part

Feature normalization Compute cost for variables

</div>
<div class="column">
multiple

</div>
<div class="column">
Submitted File

<pre>featureNormalize.m
computeCostMulti.m
</pre>
<pre>gradientDescentMulti.m
normalEqn.m</pre>
</div>
</div>
</div>
