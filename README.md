[![CircleCI](https://circleci.com/gh/phiendp/ml-microservice-kubernetes.svg?style=svg)](https://circleci.com/gh/phiendp/ml-microservice-kubernetes)

## Project Overview

In this project, we will operationalize a Machine Learning Microservice API, given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios,

### Project Tasks

The project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project we will:
- [x] Test the project code using linting
- [x] Complete a Dockerfile to containerize this application
- [x] Deploy the containerized application using Docker and make a prediction
- [x] Improve the log statements in the source code for this application
- [x] Configure Kubernetes and create a Kubernetes cluster
- [x] Deploy a container using Kubernetes and make a prediction
- [x] Upload a complete Github repo with CircleCI to indicate that the code has been tested

---

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
