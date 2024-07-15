# Kubernetes MongoDB and Mongo Express Setup

This repository contains Kubernetes manifests to deploy MongoDB and Mongo Express using Kubernetes.

## Contents

- `secret.yaml`: Secret for MongoDB credentials.
- `configmap.yaml`: ConfigMap for MongoDB initialization.
- `mongodb.yaml`: Service and Deployment for MongoDB.
- `mongo-express-app.yaml`: Service and Deployment for Mongo Express.

## Deployment Instructions

1. Apply the Kubernetes manifests:

   ```sh
   kubectl apply -f secret.yaml
   kubectl apply -f configmap.yaml
   kubectl apply -f mongodb.yaml
   kubectl apply -f mongo-express-app.yaml
