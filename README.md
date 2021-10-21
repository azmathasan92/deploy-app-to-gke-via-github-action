# Deploy App to GKE Cluster Using Github Action

This repository contains the Github Action workflow to deploy any microservice to GKE cluster. 

## To active this workflow you need to add the following secrets to github repo
```
GKE_SA_KEY
GKE_PROJECT
```

Then move the `deploy-gke.yml` file to the following directory
```
.github/workflows/deploy-gke.yml
```

Push the code to the repo then your workflow will be ready
