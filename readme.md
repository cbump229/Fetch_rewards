# Recommender Systems Problem Statement<br>
Developing recommender systems is one of the most popular applications of data science in consumer apps.<br>
Suggest a recommender system that you believe we could use at Fetch Rewards <br>
Describe the steps you would follow to develop the system Explain how you would define success <br>
[Bonus] Demonstrate one or more of your suggested approaches in any tool, on any data set of your choosing, from any domain, real or made-up

I believe that Fetch Rewards would be best served on using both item based and user based collabrative recommender systems. The item based collabrative system would be able to recommend items to a consumer based off their past purchases and the user based collabrative system would be able to recommend products based off similar purchases that consumers with similar shopping list have bought.

### Over view of steps in building a recommender system

- make sure that a clear goal is obtained 
- gather the data
- explore the data
- model the data
- evalute the model

### Define the Goal
The first step is to make sure the goal of the project is clear so that the proper tools can be put together that will most efficiently solve the problem.

### Gather the Data

The data will be downloaded or gathered from verifiable sources

### Explore the data
Once the data is obtained there are various different ways to analyze the data but I would make sure that:

- Data types for each column make sense
- Units make sense for the gathered data
- I know what missing values mean
- Min/Max Values are appropriate
- Check for duplicate rows and outliers that may adversely affect the modeling process


### Model the data 
Use the most appropriate tools to create a distance metrics between items and ratings. Currently I am familiar with using Cosine similarity or Pairwise distance.

### Evalue the Model
Test the model by seeing how accurate the predictions are to a test sample of items. I would test the model on several items that are known to be very similar to each other. 
>Example: Iron Man compared to Iron Man 2 should have be extremely close to each other in the testing phase.
