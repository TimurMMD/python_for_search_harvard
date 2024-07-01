#Introduction
###In this project was used dataset of tri-axial smartphone accelerometer data. The goal is to obtain the classification problem of identifying the exercise type according to accelerometer data. The project steps are following:
1. Inctantiate libraries of necessary tools
2. Upload the data from csv files
3. Data preprocessing to prepare it for the ML algorithm
4. Training the model
5. Make a prediction by using the trained model
6. Save the result as a new csv file
#Methods
###The datasets were checked for containing any missing value, the 'timestamp' and 'UTC time' columns format was changed to datetime as it is better for Python using. After that, the 'UTC time' column was cut in terms of unnecessity (for training were used only 'x', 'y' and 'z' accelerometer data). Formatted dataset were merged in order to keep only data that has a label for a training purpose. As the last step of data preprocessing dataset were splitted for training, testing and X, y consequently.
#Results
###The modeling results has shown low-level of accuracy ~ (<50%). Thus, the expanding the size of input data could be suggested. As the result, the model will operate with more training data and would be able to perform better. Also, the cross-validation method may vary the accuracy into higher numbers. The best running time of implementing one classification model is around 0.24 seconds.
#Conclusion
###This project is a great chance to implement ML skills, although datasets are quite small and there is no space of applying EDA knowledge. The results are not good enough, however it's understandable how to provide better ML algorithms
