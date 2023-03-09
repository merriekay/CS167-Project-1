# CS 167 Project 1: 

## Project Description: 

Choose your own Machine Learning Adventure

## Learning Objectives: 📝
For this project, you will conduct a machine learning experiment of your own design. The write up should read like a lab report in which you should explain what you did and interpret the results. This directly addresses two of the course learning objectives stated in the syllabus:
- Students will be able to create software which utilizes machine learning programming libraries in order to conduct machine-learning-based data analysis.
- Students will be able to develop and conduct machine-learning-based data analysis experiments, and they will be able to interpret and explain the results.

## Project Description: 
For this project, you are to identify the dataset you would like to utilize. I have provided several examples in class, but you have the option of using any dataset you can find.

You will be assessed on your ability to utilize algorithms and tools introduced in this class. There are some basic guidelines as to what I want to see laid out below, but you are the machine learning engineer and it is your job to draw some meaningful conclusions about the data.

For this project, you will get to choose what dataset you use. The ones we've used in class (other than Iris/Titanic/Restaurant as they're pretty small) are all fair game (pokemon, wine quality, breast cancer, spotify). I'd recommend choosing a dataset that is interesting to you--it will make the project more fun and engaging.

Here are some other possibilities--[Kaggle](https://www.kaggle.com/datasets) has many many more, as well as the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). It is a good idea to double check with me before grabbing a dataset that's not listed here:
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

## Project Expectations: ☑️
✨**New**✨: At the very top of your notebook, I'm asking that in a text cell, you **describe how many points you attempted to get from this project**. Tell me what you think you deserve on this notebook given the rubric at the bottom of this page. 

You will create a Colab notebook that includes your code and results to document your experiment. Most importantly, you will use text cells in the notebook to explain what you did, interpret the results, and make your recommendations. The written markdown protions must include the following things:
1. **Problem** [2 points]: State the problem you are trying to solve with this machine learning experiment. Include a description of the data, where you got the data, and what you're trying to predict. Is the problem a regression or a classification? What kind of metric do you plan to use to measure the performance of your model?
2.  **Data Preparation** [2 points]: Explain your data preparation. What did you have to do to get your data in shape for your experiments? Why are you certain that you data is clean and prepared for use in your algorithms? 
3.  **Research** [10 points]: Put your code and your experiments here.
    - Your research should include using the models that we've talked about in class so far--namely, a K Nearest Neighbors, weighted kNN, Decision Tree, Random Forest, as well as tuning these models (with visuals, i.e. graphs) to find the parameters that give you the best performance using an appropriate metric.
    - Does normalizing your data lead to better performance? If so, why?
4.  **Analysis** [10 points]: What did you discover? What insights/recommendations do you have? What did you find that was interesting? Which model was your best model, which models didn't work well? Why do you think this is? In general, I want a discussion of your experiment, the results, and what they mean.
5.  **Bumps in the Road** [1 point]: What challenges did you encounter? How did you overcome these challenges?


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


# Rubric and Grading
Project #1 will be graded using the following rubric. I strongly suggest evaluating your project using this rubric before turning it in.

| **Description/Writing**  |**I think I deserve** |**Actual Grade**|**Notes** |
| :------------------------------- | -------: | ----: |:---- |
| 1: Problem                       |        /2|       /2|    |
| 2: Data Prep                     |        /2|       /2|    | 
| 3: Research                      |       /10|      /10|    |
| 4: Analysis                      |       /10|      /10|    | 
| 5: Bumps in the Road.            |        /1|       /1|    |
| <b>Total                         |       /25|      /25|    </b>|


