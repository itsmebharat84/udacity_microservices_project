![Screenshot 2022-07-26 at 4 00 45 PM](https://user-images.githubusercontent.com/5491871/180985623-5f669fe5-bec7-4787-9360-acb57b5a3f39.png)

# Operationalize a Machine Learning Microservice API 
[Microservices at Scale using AWS & Kubernetes](https://learn.udacity.com/nanodegrees/nd9991/parts/7ce7318b-2e3f-4a36-918b-8c79a3c56571)

## Project Overview

To operationalize a Python flask microservices that serves out predictions (inference) about housing prices through API calls using Kubernetes. 

## Project Requirements

Project should demonstrate following tasks:
* Test  project code using linting
* Use Dockerfile to containerize this application
* Deploy containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested

---

# Implementation Guide

## Pre-Requisities 
Ensure you have following applications installed on the host. 
  1. Python3 
  2. Docker
  3. Hadolint
  4. Kubernetes (Minikube)
  
## Setup the Environment

* Create a virtualenv with Python 3.7 and activate it.  
```
python3 -m venv ~/.devops
source ~/.devops/bin/activate
```
* Run `make install` to install the necessary dependencies

## Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

## Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
