# Water-Potablility
Problem Statement
	Access to clean drinking water is a challenge that still faces many humans world wide. Though developments in filtration and access to education have greatly improved water access it’s not enough. The CDC estimates that nearly 900 million people didn’t have access to safe and clean drinking water in 2017. This problem is likely to grow as our climate continues to shift and the remaining clean water is held in increasing contention. While machine learning is not a vehicle to solve this problem in its own right it can certainly give us another set of tools to help us confront and deal with it. In this project we take a look at data related to water potability. By examining indicators like pH, hardness, the presence of sulfates, chloramines, and other measurables, we would like to be able to determine if water is safe to drink. Such a model could be instrumental in allowing local communities to make determinations about the safety and potability of their water sources, which in turn would allow that community to make informed and clear eyed decisions about their water.
	As it stands we have successfully built four working models of varying amounts of success and are in the process of continued tuning of each model in order to find the optimal hyperparameters.
 
Motivation
Water is an ongoing issue and in many places a full blown crisis. We believe water is a human right. Securing that right requires local communities to have full knowledge of their resources. We would like to contribute to that project in some way. By working on a tool that can take in data points and tell a local authority (ideally with some confidence) that their water is or is not safe to drink we believe we can contribute to that project as well as cement our understanding of machine learning fundamentals.
 
Data Source
We currently have a single dataset from Kaggle user Aditya Kadiwal. This set water_potability.csv contains 3276 observations, each containing 9 features and an answer key. The key is simply if the water is or is not potable. The feature columns include: ph, hardness, solids, chloramines, sulfates, conductivity, organic carbon, trihalomethanes, and turbidity. Each column represents a measurement of some attribute of a water source.
 
Data Set Link: 
https://www.kaggle.com/datasets/adityakadiwal/water-potability/.

Algorithms and Solution Techniques:
 
We intend to make use of the following techniques via Jupyter Notebook, and the Python libraries: pandas, NumPy, Matplotlib, and scikit-learn. 
(for MinMaxScaler and K-means, and DBSCAN). GitHub for collaboration.
	On our initial findings on the project, we are going to make use of the below: 
a)	 Pre-processing and Data Cleaning – We have cleaned the data by removing nulls, normalizing the data, and ensuring all features are the correct data types.
b)	Naive Bayes (Gaussian): Normalization, K-Cross Validation
c) 	Decision Trees: Gini vs Entropy, K-Cross Validation
d)	KNN: Normalization, K-Cross Validation, Kcross, Split Proportions, Scaling
e)	Neural Net: Activation Comparison, Alpha Comparison, Layer Size    
Comparison
	f)	Comparative Analysis: Accuracy Comparison, Learning Curves
	g)	Ensemble methods: Gradient Boosing Classifier

Challenges:
In addition to our previously stated challenges when this was a wordle project, the challenge of measuring water potability will be in making sure we understand the fundamentals of our problems, and are able to intelligently and clearly analyze and tackle it. Tuning our hyperparameters to build optimal models will continue to be our ongoing challenge.

Conclusion:
Ultimately our models were unable to find any particular patterns in our water data. The question of potability will unfortunately remain a question. Each technique and tool used seemed to chronically underfit the data which suggests there may be no underlying patterns at all. 
While our data may have been stubborn to dig through, and miserly in its findings, it offered us a valuable opportunity to put the tools of machine learning to practical use. We were able to explore the use of naive-bayes, knn, decision tree, and neural net classifiers. Additionally we explored a bevy of optimization techniques including cross k validation, normalization, gradient descent and gradient boosting, learning curves and variance vs bias analysis, and more.
