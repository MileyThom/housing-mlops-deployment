# Housing Price Prediction - MLOps Workflow

 

This repository demonstrates a simple MLOps workflow for predicting housing prices based on features like area, bedrooms, and bathrooms.

 

## Repository Contents

- `Housing.csv`: The dataset used for training the model.
  
- `model.pky`: a pre-trained model generated by train.py.

-  `app.pky`: an application for users to interface with the model and recieve predictions

 

## Usage Instructions

To run this project, you will need Python installed on your local machine. Follow these steps:

 

    Clone the repository:

   ```bash

   git clone https://github.com/<your-username>/housing-mlops-basic.git

   cd housing-mlops-basic

        Install the required Python libraries:

pip install pandas joblib gradio

        run the application

python app.py

        navigate to the web page outputted.
```

## Application instructions
 - Input the square feet and number of rooms for the house which you wish to predict the cost of and select the "submit" button.
 - The model's prediction will be outputted in the "Output" panel
 - Use the "clear" button to clear the inputs and reinput new inputs for a new prediction.
