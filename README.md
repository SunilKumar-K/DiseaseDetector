# Disease Detector

## A responsive & ergonomic website to predict the disease from given symptoms and health parameters using machine learning algorithms.

### Repo Info - There are *three branches*

#### 1) Main - Contains Readme File (Project Info)
#### 2) Server - Contains Web Hosted Project (Node)
#### 3) API - Contains ML Hosted Project (FastAPI)

### Overview :
This model predicting the disease is trained in using Machine Learning and then using a Framework called FastAPI (like flask) in python,  the model is loaded and hosted on a web hosting service. This then acts as an API that receives and sends predictions and graphs as a result to our main backend server. On the Frontend when the user input the data into the parameters, the data is sent to the backend, and then to the API  which is then predicting the outcome of the model. The result is then displayed on the frontend when received on the server.

### Features :

- Predicts disease by given symptoms and health parameters
- 3 types of disease prediction ( heart, stroke and hepatitis)
- Extensive comparsion of parameters is given through a graph
- High accuracy and easy to use interface

### Tech :
Disease Dedictor uses a number of different technologies like: <br/> <br/>

- [FastAPI] - Fast web framework for building APIs with Python
- [Scikit-learn] - Tools for predictive data analysis
- [Matplotlib] - Library for creating static, animated, and interactive visualizations
- [Numpy] -  Library used for working with array, algebra and matrices
- [Pandas] - Library used for data analysis
- [Node.js] - Evented I/O for the backend
- [Express] - Fast node.js network app framework 
- [EJS] - Embedded JavaScript templating engine
