# Wine-Classification
<img width="560" alt="image" src="https://github.com/user-attachments/assets/931abf2d-e089-4b44-a221-abaaf24cd49c" />



Italy and France are historically among the countries that produce the most prestigious wines worldwide. This dataset is the first of its kind that characterizes the Protected Designation of Origin(PDO) label wines produced in Italy and France at very high detail based on the official EU documents. This allows for the first time the analysis of more than 5000 traditional wines.

In this project, I aim to predict the country of wine origin (IT/FR) for different wines based on several features like wine color, category and maximum yield. Since the dataset is unprocessed, I begin by cleaning and preprocessing the data to prepare it for modeling. Next, I split the data into training and test to build a Logistic Regression model and a Random Forest model to predict the country of wine origin. The Random Forest model turns out to be a better fit for this data with higher values for accuracy and precision metrics. I also perform clustering on the data (k-means clustering) to predict the country of wine origin. Using the elbow method, I determined the optimal number of clusters to be 4. This opens the door for further analysis into potential classifications of the wines based on their characteristics. 
