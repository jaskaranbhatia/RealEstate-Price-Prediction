# Real Estate Price Prediction using Machine Learning
By <strong>Jaskaran Singh</strong><br>Roll No: <strong>101803660</strong><br>Batch: <strong>COE29</strong>

## Description of the Project
In this project, we use Machine Learning to predict price of a property in bangalore state of India based on certain parameters like Area, BHK, No. of bathrooms and it's location. The Machine Learning model is trained using the bengalore housing dataset which as gone a proper EDA and Data Cleaning before deploying it to Heroku server as a RestAPI.

Dataset can be found on [Kaggle](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data)

## Deployment

Client Side Application: [Link](https://jaskaranbhatia.github.io/)<br>
RESTApi Deployed on Heroku: [Link](https://realestate-restapi.herokuapp.com/)

### API Calls for RESTApi Deployed on Heroku

- /get_location_names
  - 1.1 Type: GET Request
  - 1.2 Use: Fetches list of all the locations in the Bangalore Area
   
- /predict
  - Type: POST Request
  - Use: Triggers the ML Model and predicts the pricing
  - Params: total_sqft, bhk, bath, location
