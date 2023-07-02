# Cricket Predictor

This project is an IPL win predictor that uses machine learning to predict the probability of each team winning a match based on various factors such as the target score, current score, overs completed, wickets out, batting team, bowling team, and host city.

## Requirements

To run this project, you need to have the following libraries installed:

- pandas
- numpy
- scikit-learn
- streamlit
- matplotlib

Additionally, you need the following files:

- `matches.csv`: A CSV file containing match data.
- `deliveries.csv`: A CSV file containing delivery data.

## Project Structure

The project consists of the following components:

- `IPL_prediction.ipynb`: Jupyter Notebook file containing the code for building and training the prediction model.
- `app.py`: Python script implementing a Streamlit web application for predicting match outcomes.
- `pipe.pkl`: A pickled file containing the trained prediction model.

## How to Run the Application

- Install the necessary dependencies or libraries which are mentioned in the Requirements. You can install these libraries by running the following command:

`pip install <library>`

- Open the IPL_prediction.ipynb file and run all the cells to build and train the prediction model.
- Open the terminal or command prompt and navigate to the project directory.
- Start the web application by running the following command:

`streamlit run app.py`

This will start the web application on a local server.

- Access the application by opening the following URL in your web browser:

`http://localhost:8501`

- In the web application, you will see options to select the batting team, bowling team, host city, target score, current score, overs completed, and wickets out.
- Fill in the required information and click on the "Predict Probability" button.
- The application will display the predicted probabilities of each team winning the match.

Please make sure to follow these steps in order to run the application successfully.
