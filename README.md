# Susan's Portfolio
A collection of my python projects


## Project 1: Data analysis and visualization of the Stackoverflow 2020 survey dataset using Python Libraries.

In this project, I used Python libraries such as Pandas, Numpy, Matplotlib and Seaborn to explore, clean, analyse and visualize the stackoverflow data and answer 3 age related questions.
- Downloaded the survey data from the stackoverflow website
- Performed exploratory data analysis by following the steps I wrote about in [this blog post](https://towardsdatascience.com/11-simple-code-blocks-for-complete-exploratory-data-analysis-eda-67c2817f56cd) titled '11 essential code blocks for EDA'.
- Cleaned the dataset to remove unwanted rows, engineer new features, and impute missing values.
- Performed a business understanding of the data by answering questions such as 'what is the average age that most developers learn to code?', and 'Is is hard to become a peofessional developer if you learned to code after the age of 30?'

[Blog post]

[Github code]


## Project 2: Machine learning python project to compare the performance of three algorithms: Linear regression, Decision trees, and Random forests

In this project, I sought to demonstrate the complexities of various machine learning models and test how well each predicted unseen data.
Steps:
- simulated a training and test dataset using the Numpy library.
- Used scikit-learn library to create models for linear regression, decision tree, and random forests, and fit the models to the data.
- Predicted the target variable using the various algorithms.
- Identified the best perfoming model by calculating 2 metrics; Mean squared error and mean absolute error.
[Blog post]
[Github code]

## Project 3: Web development: Used Flask and SQLAlchemy to create a Task manager and deploy on heroku.

In this project, I used the python library Flask to create a web app that accepts tasks from from a user. The user can also delete a task and update a task name.
Steps:
- created a virtual environment where I installed all the dependencies.
- Implemented the various routes in the app.py file.
- Executed an SQLAlchemy database for saving the tasks
- Created a base.html template file using html and jinja2 from which the other web pages inherit the layout theme.
- created a CSS file containing the styles for the webapp.
- Initialized a requirements.txt file that holds all the dependencies.
- Deployed the app on Heroku.
[Github code]

The following AWS Cloud Development Projects were part of a Udacity Nanodegree

## Project 4: Refactored a Monolith image-filtering application to Microservices and implemented a CI/CD pipeline using Docker, Kubernetes and Travis Ci.

•	Created a PostgreSQL database on AWS RDS for storing the app’s metadata.
•	Created an S3 bucket to store the images uploaded and displayed on the app.
•	Set up each microservice to run in its own Docker container
•	Set up Travis CI pipeline to push images to Dockerhub
•	Deployed the Dockerhub images to a Kubernetes cluster.
[Github code]

## Project 5: Deployed a serverless ‘TODO’ application using AWS Lambda and the Serverless framework

•	Implemented the backend’s handler and helper functions in the serverless.yml file.
•	Allocated the necessary AWS resources such as DynamoDB and and S3 bucket in the ‘resources’ section of the serverless file.
•	Enabled distributed tracing using AWS X-Ray.
•	Configured he frontend that required login through the Auth0 portal into the app.

## Project 6: Implemented and deployed an Image-filtering Microservice on Amazon  Elactic Bean Stalk

•	Implemented a Node-Express application that downloaded an image from a public URL, filtered the image, and returned the result.
•	Deployed the application to an Elastic Bean Stalk environment and used the endpoint’s URL to access the application.

## Project 7: Hosted a static website on Amazon S3 bucket and used CloudFront service (content delivery network) to access the cached website

•	Created a public S3 bucket on AWS and uploaded website files to the bucket.
•	Configured the bucket for static website hosting and secured it using IAM policies.
•	Used CloudFront Service to speed up content delivery and used a Cloudfront endpoint to access the website.

