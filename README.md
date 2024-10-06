## This is my first End to End Machine Learning Project
## Project Pipeline:-
##  1. Component
##      (a) Data Ingestion
##      (b) Data Transformation
##      (c) Model Trainer
##  2. Pipeline
##      (a) Train Pipeline
##      (b) Predict Pipeline
##  3. Exception Handling
##  4. Logging
##  5. Miscellaneous

#Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
