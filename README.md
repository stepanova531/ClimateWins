# ClimateWins
Machine Learning with Python as a part of Data Analytics course at CareerFoundry.
# Objective
Use machine learning to help predict the consequences of climate change.
- Finding new patterns in weather changes;
- Identifying weather patterns outside the regional norm;
- Determining whether unusual weather patterns are increasing;
- Forecasting future weather conditions and Determining the safest places for people to live.
# Scenario
ClimateWins wants to assess the tools available to categorize and predict the weather. It’s concerned with the increase in extreme weather events, especially in thepast 10 to 20 years. However, it thinks that even weather extremes could be predicted and planned for using advanced tools such as machine learning. With data from the past century, it hopes to create a model for what the future will hold.
# Data
Open source data collected by the [European Climate Assessment & Data Set project](https://www.ecad.eu/).

1- Data set based on weather observations from 18 different weather stations across Europe, which contain data ranging from 1960 to 2022. Data is available [here](https://coach-courses-us.s3.amazonaws.com/public/courses/da-spec-ml/Scripts/A2/DATASET%20weather_prediction_dataset_processed.csv)

2- Batch of four different weather conditions (cloudy, rainy, sunny, and sunrise) from [Kaggle](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset)
# Tools
Python, Jupyter Notebook, sklearn, tensorflow, keras libraries
Python scripts are available here, [Supervised Machine Leaning](https://github.com/stepanova531/ClimateWins-Unsupervised-ML/tree/main/ClimateWins/02%20Scripts%20Supervised%20ML) and [Unsupervised Machine Learning](https://github.com/stepanova531/ClimateWins-Unsupervised-ML/tree/main/ClimateWins/03%20Scripts%20Unsupervised%20ML) models.
# Insights & Recommendations
## First part of the project – Supervised Machine Learning
- K-Nearest Neighbors (KNN) algorithm as a classification model has the highest accuracy rate of 85%.
- Forest tree algorithm and Artificial Neural Network (ANN) show almost the same accuracy rate of 60%. 
- However, Forest tree gives us over-complexed tree which is difficult to interpret. 
- While ANN can be used eighter for supervised or unsupervised machine learning and has great potential for improvement. Thus, my recommendation was to use ANN model.
## Second Part of the project – Unsupervised Machine Leaning
- The hierarchical clustering with complete method results in more clusters than other methods. Thus, it may give us more opportunities for further analysis of weather patterns.
- Random Forest algorithm revealed that temperature and precipitation are the weather indicators that influence most the determination of pleasant and unpleasant weather.
- Bayesian optimization with Keras Model allows us to adjust hyperparameters and improve the accuracy of CNN (Convolution Neural Network) model from 12% to 67%.  
- CNN shows a better accuracy, 95 % in recognizing picture mages.
# Key takeaways
- Some models require data scaling, for example, KNN.
- The output of the Forest Tree model is complex and difficult to interpret and requires to be pruned.  
- Some models can be used for supervised and unsupervised machine learning, for instance ANN.
- CNN model has a better accuracy rate, 95% in recognizing picture images than predicting pleasant and unpleasant weather on our data set.
- Applying optimization techniques to determining hyperparameters can improve the accuracy rate of model. 
- Random Forest algorithm allows us to identify the most impactful weather indicators which can be a starting point for further investigation. 

