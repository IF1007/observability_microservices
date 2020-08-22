# observability_microservices
A tool to provide multi layer observability to any microservices based application

Team: Gabriel Henrique, Fagner Fernandes.

Our goal is to provide a tool that could be easily integrated to any microservices based application to provide observability.
With this approach, we can monitor the nodes, the clusters and the hole application, thus preventing failures and major errors.

To Compose our Tool, we use the ones presented below:

Prometheus - www.prometheus.io  
Grafana - www.grafana.com  
Jaeger - www.jaegertracing.io  
Kiali - www.kiali.io  
Istio - www.istio.io    
Kubernetes - www.kubernetes.io 

# Preparing your ground

If you are using Windows, you can configure your infraestructure using these tools bellow:

* Ansible - https://www.ansible.com/
* Vagrant - www.vagrantup.com/
* Virtualbox - https://www.virtualbox.org/ 

## Install virtualbox

-Go to Virtualbox website, access Downloads section and install the compatible version for your system.


## Install Vagrant

Go to Vagrant website, access Downloads section and install the compatible version for your system.


## Install ansible

Go to [Ansible Documentation Site](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#selecting-an-ansible-version-to-install) and follow the instructions there.
Since Windows is not officially supported for the Ansible Control Machine, you can try installing using a docker container as explained [here](https://stackoverflow.com/questions/51167099/installing-ansible-python-package-on-windows).

