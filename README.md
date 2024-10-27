# Credit Risk Management

## Description
A Regression type prediction model using *Random Forest Classifier* algorithm. It uses accuracy_score as the metric for prediction.

## Steps

### Building Files
1) train_model.py: which has regression model code
2) requirements.txt: which has the required library names
3) credit_risk_dataset.csv: .csv dataset which includes the data regarding counsumer forcast prediction
4) Dockerfile: which contains the commands to be run in docker

### Git & Other Commands used in Command Prompt
1) `mkdir <file_name>` to create the folder
2) `cd <file_name>` to go inside the folder
3) `git init`, initializing folder as git repository
4) manually add all the files
5) `git add .` to add all the files into git track
6) `git commit -m "<message>"`, it commits whatever is there in the track
7) `git remote add origin <GitHub repository link>`, builds connection between git and github
8) `git push --set-upstream origin master`, sends all the files from git to github.


### Jenkins
1) created a new item with item name as **<item_name>**
2) selected *Freestyle project* as the item type
3) selected *Git* in **Source Code Management**
4) added *Execute Windows batch command* step in **Build Steps**
5) Saved the Configurations
6) Clicked build now

#### Output
  ![5](https://github.com/user-attachments/assets/e2dc825e-b4b1-4c10-9919-229717c38c57)

### Dockers
1) used `cd` to go forward and `cd..` to do backward, to get to the correct path in command prompt (i.e. the folder where all the files including docerfile is located.
2) executed the command `docker build -t <docker_image_name> .` to build the docker image.
3) executed the command `docker run <docker_image_name>` to run the docker image.

#### Output
  ##### Command Prompt
 ![image](https://github.com/user-attachments/assets/638e79a6-e954-4ea8-97bb-37635a6681f8)

  
  ##### Docker Hub 
![image](https://github.com/user-attachments/assets/9846b612-6b84-4931-9498-3a41e44356c7)


