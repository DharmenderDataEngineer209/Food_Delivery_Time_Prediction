## Food Delivery Time Prediction

        This project predicts delivery time for food orders based on several factors like the delivery partner's age, ratings, and the distance between the restaurant and delivery location. It's
        a combination of data analysis, visualization, and machine learning. The goal? To make delivery predictions as accurate as possible.

        Features
                1) Distance Calculation:
                    Implemented the Haversine formula to calculate distances between restaurant and delivery locations based on latitude and longitude.

                2) Interactive Visualizations:
                    Explored relationships between delivery time and variables like distance, ratings, and vehicle type using Plotly.

                3) Neural Network Model:
                    Built an LSTM-based neural network for time series prediction to estimate delivery times.

        Key Skills

                1) Python: Used for data manipulation, feature engineering, and model implementation.
                2) Data Visualization: Created scatter plots and box plots using Plotly for insights.
                3) Machine Learning: Designed and trained a neural network with Keras for prediction.
                4) Feature Engineering: Enhanced raw data by adding a distance feature for better model accuracy.

        Visualizations
                1) Scatter Plot: Showed how delivery time correlates with distance and ratings.
                2) Box Plot: Compared delivery times based on vehicle and order type.
                3) Trendline Analysis: Added regression lines to show patterns in data relationships.

        Machine Learning Algorithm
                LSTM (Long Short-Term Memory):
                        LSTMs are great for sequential data. Delivery times often depend on patterns like age, ratings, and distance, which are sequentially linked.
                        Definition: LSTM is a type of recurrent neural network (RNN) designed to remember long-term dependencies in data.


        How It Works
                1)  Data Preparation:

                        Cleaned and processed the data.
                        Added a new feature, "distance," using latitude and longitude.

                2) Model Training:

                        Input features: Delivery partner's age, ratings, and distance.
                        Output: Predicted delivery time.
                        Trained the LSTM model using Keras with an Adam optimizer and mean squared error loss function.

                3) Prediction:

                        Inputs are user-provided values for age, rating, and distance.
                        Outputs the predicted delivery time.
