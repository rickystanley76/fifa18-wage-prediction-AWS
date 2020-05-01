# fifa18-wage-prediction-AWS
Problem description</br> 
FIFA 18 Complete Player Dataset from Kaggle.com  </br>
17k+ players, 70+ attributes extracted from the latest edition of FIFA  I am going to create a model from where club owners can find out or suggest the wage of a player while hiring them into the club.

# Model Creation
I have used random forest with hyperparameter tuning to have the best model.</br>
I have tested with many difffernt tools and algforothms. 
Best one i have found is Scikit learn and Flask to deploy that in AWS EC2.

# Model Deployment
Model is deployed unsing Flask and AWS EC2 as an web interface.

# Intallation Process: 
1. Launch one EC2 intance in AWS according to your choice. (I have used Ubuntu 18 )
2. Upload the files and folders to the home folder /home/ubuntu (I have used winSCP to upload)
3. Use Putty to connect to the EC2 intance.
4. Run the following command:
  a. sudo apt-get update && sudo apt-get upgrade
  b. sudo apt-get install python3-pip 
  c. pip3 install -r requirements.txt
5. To run the app: python3 app.py
6. the URL: http://yourIP:8080


