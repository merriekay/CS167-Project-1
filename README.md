# CS 167 Project 1: 

## Project Description: Dataset Choice

For this project, you will get to choose what dataset you use. The ones we've used in class (other than Iris/Titanic as they're pretty small) are all fair game (pokemon, wine quality, breast cancer, spotify). I'd recommend choosing a dataset that is interesting to you--it will make the project more fun and engaging.

Here are some other possibilities--Kaggle has many many more. It might be a good idea to double check with me before grabbing a dataset that's not listed here:
- 🥑 [Avocado Prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)
- 🎟️ [Admission to University](https://www.kaggle.com/datasets/akshaydattatraykhare/data-for-admission-in-the-university)
- 🏎️ [Speed Dating](https://www.kaggle.com/datasets/whenamancodes/speed-dating)
- 🎓 [World University Ranking](https://www.kaggle.com/datasets/whenamancodes/world-university-ranking-2022-2023)
- 📸 [Top Instagram Influencers](https://www.kaggle.com/datasets/whenamancodes/top-200-influencers-crushing-on-instagram)
- 🌦️ [Weather Prediction](https://www.kaggle.com/datasets/thedevastator/weather-prediction)
- 🤑 [Student Monthly Expenses](https://www.kaggle.com/datasets/shariful07/nice-work-thanks-for-share)
- 🍺 [Student Alcohol Consumption](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption)
- 🏫 [College Score Card](https://www.kaggle.com/datasets/thedevastator/u-s-department-of-education-college-scorecard-da)
- 🎮 [IMDB Video Games](https://www.kaggle.com/datasets/muhammadadiltalay/imdb-video-games)
- 🎵 [Spotify Recommendation](https://www.kaggle.com/datasets/bricevergnou/spotify-recommendation)

# Project #1 Expectations: Written Portion
You will submit a link to your GitHub repository which includes your code and results to document your experiment.
And, most importantly, you will use markdown cells in the notebook to explain what you did, interpret the results, and draw conclusions.

The written markdown portions must include the following things:
1. __Name__: include your name at the top of the notebook
2. __Data Description__: Answer the following questions:
    - Explain what dataset you chose, and why you chose it. 
    - Specify which columns you are using as your __predictor variables__
    - What variable are you selecting as your __target variable__? 
    - In selecting this target variable, does this make your problem a __classification__ or a __regression__? 
3. __Research Question__: As clearly/specifcially as possible, state the question you are trying to solve in this project.
    - For example, if I was working with the Iris dataset, I might ask 'how accurately can we predict the species of Iris from these 4 measurements?'
4. __Data Preparation__: Explain what pre-processing steps you chose to do to get your dataset in shape for your experiments. (e.g. creation of dummy variables, filling in missing values, normalization, etc.) 
5. __Metrics__: Identify which metrics you will be using to test your model and say why they are appropriate.
6. __Baseline Performance__: Identify a baseline for your metrics--what woudld you expect to happen with this particular data if you always guessed the average or if you guessed randomly? Use `sklearn.dummy` to establish this baseline.
7. __Model Planning and Execution__: Identify which learning algorithms you have tried and which important parameteres you've tuned for each one. 
8. __Results__: After you conduct your learning experiment, summarize the results you got. Include visualizations (i.e. graphs) where appropriate. How did you find the best k, n, m, or other variables that you needed to tune?
9. __Bumps in the road__: What challenges did you encounter? How did you overcome these challenges? Did you have to adapt your strategy to account for these challenges? Why or why not?
10. __Conclusions__: What insights/recommendations do you have? What di dyou find that was interesting? Which model was your best model, which modles didn't work as well? Why do you think this is ? In general, I want a discussion of your experiment, the results, and what they mean. 

# Project #1 Expectations: Code Portion

For full credit, your experiments should include the following models:
- __k Nearest Neighbors__
- __weighted k Nearest Neighbors__
- __decision tree__
- __random forest__ 

You need to demonstrate the performance of these models on both __normalized__ and __non-normalized__ data. 

For each of the above models, you need to include a __graph of at least 1 tuned parameter__. 

Essentailly, you will be able to fill out this chart with your results:

| **Model**     | **Non-Normalized** | **Normalized** | **Parameter Tuned** |
|---------------|--------------------|----------------|---------------------|
| kNN           |                    |                |                     |
| w-kNN         |                    |                |                     |
| decision tree |                    |                |                     |
| random forest |                    |                |                     |



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
| **Description/Writing**  |**Points taken**  |**Notes** |
| ------------------------------- | ------------------- | --------- |
| 1: Name                         |        |    |
| 2: Data Description             |        |    | 
| 3: Research Question            |        |    | 
| 4: Data Preparation             |        |    |
| 5: Metrics                      |        |    | 
| 6: Baseline Performance         |        |    |
| 7: Model Planning and Execution |        |    |
| 8: Results                      |        |    |
| 9: Bumps in the Road            |        |    | 
| 10: Conclusions                  |        |    |
| <b>Total                        |       /10 | </b>   |


| **Code**  | **Points Awarded**  (1 point each) | **Notes** |
| --------- | ------------------- | --------- |
| knn                             |        |    |
| graph of knn parameter          |        |    | 
| weighted knn                    |        |    |
| graph of weighted knn parameter |        |    | 
| decision tree                   |        |    |
| graph of decision tree parameter|        |    | 
| random forest                   |        |    |
| graph of random forest parameter|        |    |
| feature importances chart       |        |    | 
| normalized knn                  |        |    |
| normalized weighted knn         |        |    |
| normalized decision tree        |        |    | 
| normalized random forest        |        |    |
| <b>Total      |       /13 | </b>   |

| **Written Portion**  | **Code Portion**   | **Total** |**Notes** |
| --------- | ------------------- | --------- |--------- |
|         /10  |                 /13    |        /23   |           |


