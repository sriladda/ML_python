# predict when the machine is in danger of failing.
This exercise is based on a real world problem involving the operation and maintenance of a large machine in a factory. The machine has been observed to occasionally fail. This not only results in expensive repairs, but can also be potentially dangerous to the operators. So, our objective is to predict when the machine is in danger of failing.

In order to be able to make predictions, we have at our disposal a number of measurements that are continuously recorded by sensors attached to the machine. Further, for each of those measurements, we also have a historical record of the health of the machine. We need to use this information to build a classifier which can be used to make predictions.

# Learning goals

There are some very important learning goals within this exercise:

**Feature encoding:** Some of the measurements are numerical and some are categorical i.e. Low/Medium/High. In order to build a classifier, the categorical measurements have to be converted to numerical ones.

**Training / Testing split:** The only way to find out if a machine learning model is good is by feeding it with separately held test data and checking its actual performance against the expected accuracy based on the training set.

**Scaling:** Machine learning models (usually) require all numerical features to have similar ranges. If the original features have dissimilar ranges, they must be rescaled to make them more similar.

**Performance Evaluation:** How do we measure the effectiveness of a classifier? Having taken a lot of trouble to train a classifier, we need to be able to make predictions about how well it will perform on new, unseen data. We will introduce several metrics to measure performance.

**Comparison of multiple classifiers:** It should become routine practice for you to try out several classification methods and summarize the results in an easily understandable way.

One sentence summary goes here saying what you did.
A second sentence goes here says why it matters.
A last sentence links to any productionized web dashboard here.

You can also link to 
* [Your Email]()
* [Your Linked In]()
* [Your Twitter?]()

> We suggest that people follow a "Facebook Page" approach to writing up their README. This means that the most important information is at the top (your name, point of project, contact info) and then as you go down the document you get less and less relevant information. Remember that you are NOT writing a detective story and need to find a way to present as much information as quickly as possible to the person that will be looking at this for 45 seconds tops. Of course others might look for longer, but the UX/UI of your REAMDE should be done with the 'github skimmer' in mind.

### Executive Summary

Start with one or two sentences here that contextualises what your project matters here.
These two sentences will demonstrate your business understanding. 

Next, in a second paragraph, write how you were able to make a data science operationalization of the problem.
For example, you might say that in order to help solve this problem you set out to build a classification ML model in order to automate some process. 

Third, you then write what you did on the project that is a bit more technical.
Here you might say that you took data from [here and make it a link to the original data]() and then ran `a list of models you ran here` in your analysis.
Then end with one sentence that picks what your best model was and how it performed.

Lastly, you say in one or two sentences why this matters. 
For example, now as opposed to before this data analysis, you can now predict X better than Y. 

The goal of this project was to create a `regression/classification` model that was able to predict `what you set out to do`.

> If you are able to swap out the text here with what your case example is you will demonstrate the following:
> 1. You get why what you're doing 'matters'
> 2. You are able to take ill defined problems and turn them into something a data scienst can solve
> 3. You show off your analystical and modeling chops.
> 4. You are able to communicate technical things you do.

### More Information

Below your Executive Summary, you can document whatever you feel would be of interest to a future employer.
Here I would especially suggest diving a bit deeper into your methodology and including images that you are proud of from the project. 
Remember, that people will probably judge your github project page within 45 seconds tops, you want it to look as clean as possible. 

Write documentation that looks like someone you would want to work with.

### Show Off Your Data Viz

![Everyone Likes a Pairplot](figures/seaborn-pairplot-3.png)

> Image taken from `seaborn` [documentation](https://seaborn.pydata.org/generated/seaborn.pairplot.html)

**DO NOT PUT THE GOOD BITS OF YOUR PROJECT BURRIED AWAY AT THE BOTTOM OF YOUR README, YOU ARE NOT WRITING A DETECTIVE NOVEL**


