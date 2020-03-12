[![CircleCI](https://circleci.com/gh/ahmedmater110/Operationalize_ML_Microservice/tree/master.svg?style=svg)](https://circleci.com/gh/ahmedmater110/Operationalize_ML_Microservice/tree/master)

Project Overview:

In this project, You are given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, 
such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. 

Project Tasks:

python app:
 "app.py" is our python application
 # python /app/app.py
 
Docker:
we have three files, "Dockerfile" contains all commands to build our image, 
                     "run_docker.sh" script to build docker image and create a container,
                     "upload_docker.sh" to upload our image to Docker Hub.
					 
Kubernetes:
we have on file called "run_kubernetes.sh" to build the kubernetes cluster.

Test:
"make_prediction.sh" is a script to test our app.
