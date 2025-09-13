Task
Analyze the provided dataset "/content/sorting hat - Sheet1 (5).csv" to build an AI system that sorts individuals into Hogwarts houses based on their personality, choices, and responses.

Load the data
Import the pandas library and load the dataset into a pandas DataFrame. Then, display the first 5 rows and the info of the DataFrame to understand its structure and data types.
Explore and preprocess the data
Analyze the data to understand its structure, identify relevant columns, and handle any missing values or inconsistencies.
Examine the unique values in the 'HOUSE' column, check for inconsistencies, analyze the text column for patterns and cleaning needs, and determine if there are any missing values.
Based on the initial analysis, the 'HOUSE' column has consistent values. The text column appears to contain free-form text requiring standard text cleaning. There are no missing values. The next step is to outline necessary preprocessing steps for the text data.
Extract relevant features from the text data using techniques like TF-IDF or word embeddings.
Select a suitable machine learning model for classification (e.g., a sentiment analysis model or a personality prediction model) and train it on the prepared data.
Assess the performance of the trained model using appropriate evaluation metrics.
Create a function or class that takes new input (personality, choices, responses) and uses the trained model to predict the most suitable Hogwarts house.
Use the `predict_house` function (already defined) to predict the house based on the processed user input.
Implement a loop to guide the user through the quiz, collect responses, process them, predict the house, and display the result, with an option to exit.



