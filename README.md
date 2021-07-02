# CS 167 Project 1: 
## Learning Objectives: 
For this project, you will use the scikit-learn library to conduct a machine learning experiment, and your write-up will ask you to explain what you did and interpret the results. This directly addresses two of the course learning objectives stated in the syllabus:
- Students will be able to create software which utilizes machine learning programming libraries in order to conduct machine-learning-based data analysis.
- Students will be able to develop and conduct machine-learning-based data analysis experiments, and they will be able to interpret and explain the results.

## Project Description:
For this project, I'm giving you a choice of what dataset you would like to use. The options are:
- NCAA March Madness Predictions 🏀 ⛹️‍♂️
- World Happiness Rankings 😄

I have provided starter code for each of these two problems that describe and import the data. The rest of the experiment is up to you. This project should read more like a lab report than a coding assignment. I want to be able to see what you are thinking and how you are going about solving the problem that you state using the data and the tools that you have learned in this class so far. There are some basic guidelines as to what I want to see laid out below, but you are the machine learning engineer and it is your job to draw some meaningful conclusions about the data. 


## Project Expectations: ☑️
You will create a Colab notebook that includes your code and results to document your experiment. Most importantly, you will use text cells in the notebook to explain what you did, interpret the results, and make your recommendations. The written markdown protions must include the followint things:
1. **Name**: Include your name at the top of the notebook. 
2. **Problem**: State the problem you are trying to solve with this machine learning experiment. 
3. **Data Preparation**: Explain your data preparation. What did you have to do to get your data in shape for your experiments - creation of dummy variables, filling in missing values, etc. 
4. **Metrics**: Identify which metrics you will be using to test your model, and say why they are appropriate. 
5. **Baseline Performance**: Identify a baseline for your metrics - what would you expect to happen with this particular data if you always guessed the average or if you guessed randomly? What did some of the unsuccessful machine learning algorithms yield?
6. **Model Planning and Execution**: Identify which learning algorithms you will try and which important parameters you will tune for each one. 
7. **Process**: Describe how you went about solving this problem. What did you try first, second, third, etc.. How are you certain that your answer is correct?
8. **Results**: After you conduct your learning experiment, summarize the results you got. Include visualizations as appropriate. 
9. **Recommendation**: Make recommendations about how you would fill out a bracket given these predictions
10. **Insights**: Give any additional secondary insights/outcomes that you have gained from this experiment - anything that you think might help the business. Is there something interesting you discovered about the data that sheds light on something that's happening? Is there anything meaningful in the shape of a decision tree, performance of some subset of the data, etc. 

### Your Experiments should Include:
- A k Nearest Neighbors model with at least 1 tuned parameter
- A Decision Tree model with at least 1 tuned parameter
- A Random Forest model with at least 1 tuned parameter and feature importance chart
- Normalize your data and try the above models again (no need to tune your parameters this time unless you want to). 

## Notes, Tips and Tricks

### What does it mean to tune parameters?
Tuning parameters means that you try your model with different values for that parameter and record how well the resulting model performs on the test set 📈. This is what you did in Notebook 3 when you tried different k, graphed them and found the value of k that resulted in the best model. You found the best k for k-NN, so that means you tuned k. For this project, you are strongly encouraged to try tuning more than one parameter for each model. You should make sure to pick a parameter that actually has an important effect on your model/data, and explain why you chose the parameters you chose in your text description.

### Where should I start?
Copy and paste the above 10 items into a markdown cell, and begin answering the questions that you can answer before you even start coding.

Use the template for building and testing a scikit-learn model. Start by doing the following:
- Change that example code to work with your new data
- Look for the appropriate documentation for the scikit-learn modules for the machine learning algorithms we have discussed in class: http://scikit-learn.org/stable/modules/classes.html .
- Try to produce a plot like the one you did in Notebook 3, but use scikit-learn like in the example for random forests

# Rubric and Grading
| **Description/Writing**  |**Points Awarded** (1 point each)  |**Notes** |
| --------- | ------------------- | --------- |
| 1: Name      |        |    |
| 2: Problem      |       |    | 
| 3: Data Prep      |        |    |
| 4: Metrics      |        |    | 
| 5: Baseline Performance      |       |    |
| 6: Model Planning and Execution      |        |    |
| 7: Process      |        |    | 
| 8: Results      |        |    |
| 9: Recommendations      |        |    | 
| 10: Insights      |        |    |
| <b>Total      |       /10 | </b>   |


| **Code**  | **Points Awarded**  (1 point each) | **Notes** |
| --------- | ------------------- | --------- |
| knn      |        |    |
| graph of knn parameter      |       |    | 
| decision tree      |        |    |
| graph of decision tree parameter      |        |    | 
| random forest      |       |    |
| graph of random forest parameter      |        |    |
| feature importances chart      |        |    | 
| normalized knn      |        |    |
| normalized decision tree      |        |    | 
| normalized random forest      |        |    |
| <b>Total      |       /10 | </b>   |

| **Written Portion**  | **Code Portion**   | **Total** |**Notes** |
| --------- | ------------------- | --------- |--------- |
|         /10  |                 /10    |        /20   |           |


