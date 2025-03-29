kubectl create namespace jenkins -> create a namespace for the new app
kubectl apply -f . -n namespace jenkins -> run container in the folder where you have the config files
kubectl get pods -n jenkins -> check pod status
kubectl exec --stdin --tty <POD-NAME> -- /bin/bash -> connect to container's shell to retrieve admin password for jenkins setup
