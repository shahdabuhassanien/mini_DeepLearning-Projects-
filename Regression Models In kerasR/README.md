# Predicting City-Cycle Fuel Consumption Using Vehicle Attributes

Author: Shahd Abu Hassanien 

## Business Problem : 
How can we accurately predict a vehicle’s fuel consumption (in miles per gallon) based on its characteristics?
Efficient fuel consumption prediction helps automotive manufacturers, environmental agencies, and consumers make informed decisions to improve fuel economy, reduce emissions, and lower costs.

## Data:

The dataset is sourced from the University of California, Irvine (UCI) Machine Learning Repository and was introduced in Quinlan (1993).
It contains:

Target variable: City-cycle fuel consumption in miles per gallon (mpg)

## Methods

1. **Data Preprocessing**  
   - Cleaned and preprocessed the dataset to handle missing values and ensure data quality.  
   - Split the dataset into training and testing sets to evaluate model performance effectively.

2. **Model Building**  
   - Created a Sequential model using deep learning techniques suitable for regression tasks.  
   - Incorporated Dropout layers to prevent overfitting and improve generalization.

3. **Training**  
   - Trained the model with Early Stopping to halt training when the validation loss stopped improving, preventing overfitting and saving time.

4. **Evaluation**  
   - Evaluated the trained model using appropriate regression metrics to assess its predictive performance on unseen data.
  


## Results : 

<img width="590" height="1190" alt="image" src="https://github.com/user-attachments/assets/457de8a6-cb54-4b9e-89e8-7a98bdf1d275" />

### Loss Curve During Training:  

This plot shows the training and validation loss across epochs. Both losses decrease consistently, indicating that the model is learning well and generalizing properly to unseen data. The closeness between the training and validation loss curves suggests that the model is not overfitting, and the training process is stable

