# fifa18-wage-prediction-AWS
Problem description</br> 
FIFA 18 Complete Player Dataset from Kaggle.com  </br>
17k+ players, 70+ attributes extracted from the latest edition of FIFA  I am going to create a model from where club owners can find out or suggest the wage of a player while hiring them into the club.

# Model Creation
I have used random forest with hyperparameter tuning to have the best model. I have tested with many difffernt tools and algforothms. 
Best one i have found is Scikit learn and Flask to deploy that in AWS EC2.

# Model Deployment
Model is deployed unsing Flask and AWS EC2 as an web interface.

# URL: 
http://ec2-54-93-84-142.eu-central-1.compute.amazonaws.com:8080/
