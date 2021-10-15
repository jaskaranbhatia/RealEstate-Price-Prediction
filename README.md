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

###  Technologies Used
- Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn
- Jupyter Notebooks
- Flask (For Backend and Deploying ML Model)
- HTML/CSS (For Frontend)
- JQuery (For Making API Calls to Flask RESTApi)

### Novelty of the Project
- There do exist some projects which predict the house pricing based on data but this one is one of it's kind. I have attempted and given high priority to Exploratory Data Analysis which helped in data cleaning, outlier detection and filling the missing values. Because of properly cleaned data, have recieved great accuracy with Multiple Linear Regression, Lasso Regression and Decision Trees.
- Also, I have created a RESTApi using Flask so that in future we can use this API with mobile app as well along with the web app. So, this provides a great option for scalibility as frontend and backend are deployed seperately. Will some other apps combine server and client side which makes the app less scalable.

### Screenshots
![Capture0](https://user-images.githubusercontent.com/43378659/137434229-119c91b5-51dd-471d-aa13-93b7ffbf7f9f.PNG)

![Capture2](https://user-images.githubusercontent.com/43378659/137434241-50ef3976-16ba-42ed-b9ed-78f2cb134bc4.PNG)

![Capture](https://user-images.githubusercontent.com/43378659/137434253-a5128725-2ad2-4592-93ab-31bf281375db.PNG)



