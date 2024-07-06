# Wide-and-Deep-Learning-Book-Recommendation-System


This repository contains the code and resources for building a book recommendation system using a Wide and Deep Learning model. The system leverages user ratings data to provide personalized book recommendations based on the architecture described in this paper (https://arxiv.org/pdf/1606.07792). The model combines the benefits of linear models (wide) and deep neural networks (deep) to capture both memorization and generalization capabilities.

Dataset

The dataset is sourced from the Book-Crossing dataset on Kaggle. It consists of three CSV files:
* BX-Users.csv: Contains user information.
* BX-Books.csv: Contains book information.
* BX-Book-Ratings.csv: Contains user ratings for books.

Installation

To get started, clone the repository and install the required packages:
git clone https://github.com/yourusername/book-recommendation-system.git
cd book-recommendation-system
pip install -r requirements.txt

Usage

Data Preprocessing
1. Load and Merge Data: Load the users, books, and ratings data, and merge them into a single DataFrame.
2. Clean Data: Remove unnecessary columns and handle missing values.
3. Encode and Scale Features: Encode categorical features and scale numerical features.

Model Training
1. Split Data: Split the data into training and testing sets.
2. Define Model: Define the Wide and Deep Learning model.
3. Prepare Inputs: Prepare wide and deep inputs for the model.
4. Train Model: Train the model using an optimizer and loss function.

Evaluation
Evaluate the model on the test set.

Recommendation
Use the trained model to recommend books for a specific user.
