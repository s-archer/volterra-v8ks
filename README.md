YAML file to create a simple, single-microservice application.  

Contains:

- a deployment with single pod (replicas). Increase from 1 to see responses from multiple pods.
- a service (ClusterIP) to provide access to the pods. 

You can deploy both of these in a single action using `kubectl apply -f <filename>` or use the vk8s UI in Volterra and add the Deployment and Service separately in the appropriate sections of the UI.
