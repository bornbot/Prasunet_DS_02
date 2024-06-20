# Project Overview
This repository is my Task 2 submission for the Data Science internship at Prasunet Company. It involves data cleaning, EDA, and feature engineering on the Titanic dataset from Kaggle to explore relationships, identify patterns, and create new features for better predictive modeling.

## Files in the Repository
- **DS_02.ipynb**: Jupyter Notebook containing the analysis, data preprocessing, feature engineering, model training, and evaluation steps.
- **gender_submission.csv**: A sample submission file in the correct format for submission to Kaggle.
- **test.csv**: The test dataset used to evaluate the performance of the trained model.
- **train.csv**: The training dataset used to build and train the machine learning model.

## Project Structure
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
- **Exploratory Data Analysis (EDA)**: Visualizing the data to understand distributions and relationships between features.
- **Feature Engineering**: Creating new features and selecting the most relevant ones for the model.
- **Model Training**: Implementing various machine learning algorithms and tuning hyperparameters.
- **Model Evaluation**: Assessing the model's performance using metrics like accuracy, precision, recall, and F1-score.
- **Prediction and Submission**: Generating predictions on the test set and preparing the submission file.

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Installation
Clone the repository and navigate to the project directory:
```bash
git clone <repository-url>
cd <repository-directory> 
```
Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
### Running the Project
Open the Jupyter Notebook:
```
jupyter notebook DS_02.ipynb
```

Follow the steps in the notebook to preprocess the data, train the model, and make predictions.

## File Descriptions
### DS_02.ipynb
Contains the entire workflow of the project:

- Data loading and inspection
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Model selection and training
- Model evaluation
- Prediction and submission

### gender_submission.csv
A sample submission file provided for the Kaggle competition. It contains a sample prediction of whether a passenger survived or not.

### test.csv
The test dataset that needs to be used to make final predictions. It includes the same features as the training set but without the target variable.

### train.csv
The training dataset used to build and train the predictive model. It includes features like PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked, and the target variable Survived.

## Conclusion
This project aims to build a robust predictive model for Titanic survival prediction using machine learning techniques. By following the steps outlined in the Jupyter Notebook, you can replicate the analysis and model building process. Feel free to explore, modify, and improve the code to enhance the model's performance.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- The Titanic dataset is provided by Kaggle as part of their Titanic Machine Learning from Disaster competition.
- Thanks to the open-source community for their contributions to the tools and libraries used in this project.