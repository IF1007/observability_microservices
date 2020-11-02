# observability_microservices
A tool to provide observability at a given container for any microservices based application.

Team: Gabriel Henrique, Fagner Fernandes.

Our goal is to provide a tool that could be easily integrated to any microservices based application to provide observability.
We use a mix approach, so our tool can booth execute the observability task on a active or on a passive way. 

To Compose our Tool, we use the ones presented below:

Prometheus - www.prometheus.io  
Grafana - www.grafana.com  
CAdvisor - https://github.com/google/cadvisor

# Preparing your ground

Regardless the operation system that you are using, we will need:

* Docker - https://docs.docker.com/get-started/
* Python 3 - https://www.python.org/downloads/
* Jupyter Lab - https://jupyter.org/install.html

## Deploying Our Observability Stack

* Clone this project 
* Enter compose-setup
* Do docker-compose up -d

## Using the Capture and Analysis Module

* Clone this project
* Do jupyter-lab
* Override some especif informations like 'url' and 'emails' and run those cells