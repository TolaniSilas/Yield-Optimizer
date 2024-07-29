# Yield Optimizer: Predicting Suitable Crops Based on Soil Composition




## Overview 
Yield Optimizer is a machine learning project designed to predict the most suitable **crop type** for a given soil sample based on its **nutrient composition**. By leveraging data on **soil nutrients** and **pH levels**, the model helps optimize crop selection, leading to better yields and more efficient use of resources.



## Table of Contents
1. Project Motivation
2. Installation
3. Usage
4. Application Features
5. Dataset
6. Modeling Approach
7. Results
8. Contributing
9. Contact



## Project Motivation
Selecting the right **crop** for a specific soil type is crucial for maximizing agricultural yield and sustainability. Farmers often face challenges in determining which crops will thrive in their soil based on its nutrient composition. This project aims to provide a solution by using machine learning to predict crop suitability based on soil data.



## Installation
To get started with **YieldOptimizer**, follow these steps:
1. ### Clone the repository:
    git clone https://github.com/TolaniSilas/YieldOptimizer.git <br>
    cd YieldOptimizer

2. ### Set up a virtual environment:
    python -m venv venv
    venv/Scripts/activate

3. ### Install the required packages:
    pip install -r requirements.txt



## Usage
The **YieldOptimizer application** provides a user-friendly interface to predict the most suitable **crop type** for a given soil sample based on its nutrient composition. Follow these steps to use the application:

1. ### Run the Application:
- #### Start the application server:
    python yield-optimizer-app.py

- Open your web browser and go to http://yield-optimizer to access the Yield Optimizer app interface.

2. ### Use the Application:
- #### Input Soil Data: Enter the soil's nitrogen, phosphorus, potassium levels, and pH value into the form provided in the app.
- #### Get Predictions: Click the "Predict" button to receive the recommended crop type for the input soil composition.



## Application Features
- User-Friendly Interface: Easy navigation and input for soil data.
- Real-Time Predictions: Immediate feedback on the most suitable crop based on input data.



## Dataset
The dataset used in this project includes features such as the levels of **nitrogen**, **phosphorus**, and **potassium**, along with the soil's **pH value**. Each entry corresponds to a farmland plot with an associated **crop type**. The data was sourced from [insert source], and can be found [here](link to dataset if publicly available).



## Modeling Approach
The project involves the following steps:

1. Data Preprocessing: Handling missing values, handling duplicates, outlier detection and normalizing nutrient levels.
2. Feature Engineering: Selecting relevant features that contribute to the prediction of crop types.
3. Model Selection: Experimenting with various machine learning models, such as **Random Forest**, **Gradient Boosting**, **eXtreme Gradient Boosting** and **Neural Networks**, to find the best performing model.
4. Model Evaluation: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.



## Results
The best-performing model achieved an accuracy of % on the test dataset. The results demonstrate the model's ability to reliably predict the most suitable **crop type** for a given soil sample.



## Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: git checkout -b feature-name.
3. Make your changes and commit them: git commit -m 'Add new feature'.
4. Push to the branch: git push origin feature-name.
5. Submit a pull request.



## Contact
For questions or suggestions, please reach out via Twitter or GitHub.
