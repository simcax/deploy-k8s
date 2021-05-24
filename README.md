# deploy-k8s
My early work figuring out how to get a Kubernetes Cluster running on Raspberry Pi 4b nodes. 

This is not really working stellar yet, but I guess it can be used as inspiration :-) 

The initial setup works, for configuring each Pi with basic settings needed prior to installing microk8s. 
I don't have the add-node part working entirely I must say, and I am waiting for my next pi to arrive in order to test it out again. 

There are some pitfalls in the area about adding nodes, where they need to be done one at a time, each getting a unique token. So that is my next area of exploration. In addition this needs to be made into an ansible role ;-)
