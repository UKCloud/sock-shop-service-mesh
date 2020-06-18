# The Sock Shop for Service Mesh

This repo contains automation to install the WeaveWorks Sock Shop sample application into OpenShift to use with the OpenShift Service Mesh Operator.

## Pre-requisites

You should already have installed the OpenShift Service Mesh Operator and all it's pre-requisites first. See https://docs.openshift.com/container-platform/4.4/service_mesh/service_mesh_install/preparing-ossm-installation.html for details.

## Using this repo

Ensure you are logged in to the cluster you want to deploy the sock shop into.
Optionally add the domain suffix to the sock-shop-control-plane.yml and run that playbook if you want a dedicated control plane.
Add the domain suffix and the control plane project to the sock-shop-data-plane.yml playbook and run that to install the sock shop into it's own project.

## About the Sock Shop

See https://microservices-demo.github.io/docs/
