# Service YAML file for building Pod

This is the file which kubernetes uses to build a service to connect to the pod

A pod is what runs 1 or more containers inside

the service will be connected to the pod and thats how the program runs

The following command is the one i used to build the pod.yaml

- kubectl apply -f . to run both yaml files

Then i can connect to the service through the Node Port and see the stuff
