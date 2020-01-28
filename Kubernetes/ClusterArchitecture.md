### Cluster Architecture

Kubernetes cluster have two roles:
 1. Master node (Control Plane)
 2. Worker node (Minion node)

# Master node

The main reason for this role is to control everything what happens in cluster.
Also all requests goes through Master Node's component called **API server**.
When you creating some resourse through a command **kubectl**, which is main tool for communicating with API server, 
another component looks to free resources and other workload-specific requirements on Worker Nodes
and assigns requested resources.

# Worker node