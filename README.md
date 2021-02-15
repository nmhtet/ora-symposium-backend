# se-symposium-backend-api
A simple Stateless , Highly scalable Express Based REST API build on MERN Stack. Built for a symposium at Oracle 

# MERN Stack App for Social Back Ends 
* Likes 
* Posts
* Meet Now 
* Events

## Step 1: Create a Kubernetes Namespace 
``` kubectl create namespace my-namespace ```

## Step 2 : Deploy Mongo DB to the cluster
### Works on Oracle OCI 

```!! Note PVCs are automatically spawned based on the K8s-Volume Provisioner ```

``` helm repo add stable https://kubernetes-charts.storage.googleapis.com/ ```

``` helm install --name my-release --namespace my-namespace stable/mongodb-replicaset ```

### What is Included in the repo
* A NodeJS REST Api container
* k8s- replica set config 

## Step 3 : Deploy API Backend Layer 


Test Test


