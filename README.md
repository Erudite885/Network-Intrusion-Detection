# Network-Intrusion-Detection-Using-Deep-Learning
## Objective : 
Cyber Security: Development of Network Intrusion Detection System (NIDS),   with Machine Learning and Deep Learning, Recurrent Neural Network models, MERN web I/O System.
## To run locally on your system:
### Method - 1 :-
step-1: Keep the Docker Desktop and Docker Hub running parallelly on your system then open the command prompt or terminal and run the following command [docker run --publish 3000:3000 saif0786/nids].

step-2: You can now check the running of the service on your browser by typing [http://localhost:3000] as per shown above.

### Method - 2 :-
Step-1 : Fork or Clone the project using command [git clone <url>]   
Step-2 : Create a .env file and set up the dovenv variable which is used in app.js 
Step-3 : Use command [npm install] to install all the packages.                                                                                                          
Step-4 : Use command [node app.js] to run it locally.
## Description : 
Large numbers of businesses were affected by data infringes and Cyber -attacks due to dependency on internet. To prevent such malicious activity, the network requires a system that detects anomaly and inform the user and alerts the user. 

![temp](https://user-images.githubusercontent.com/106341416/189742718-d621c3ad-ed1d-4b7b-b39a-f41d8fd0bc95.png)

This project detects Network Intrusion anomalies by using NSL - KDD data-set. The deep learning model Long Short Term Memory (LSTM), superior version of RNN (Recurrent Neural Network) and KNN K - Nearest Neighbour Algorithm) method are used for binary and multi class classification. 

The user enters the hacking parameters in the front end which is designed by using ReactJS. The model predicts the type of attack and gives information about the type of attack to the user. MongoDB is used for storing the data and NodeJS is served as back end framework.

The project is fully responsive and completely based on session and cookies concepts. Once the user authenticated and logged-in It will not ask the user to enter the login parameters again and again (next visit). It ask login parameters only when user click on logout button. And also using google oauth 2.0 for user authentication and storing user details in salted hash in the mongoDB.

## Some Screenshots: 
