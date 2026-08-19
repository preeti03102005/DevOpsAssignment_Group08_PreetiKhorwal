# Assignment 1: Creating a Kubernetes Pod

## Aim

To create and run a Kubernetes Pod using a YAML configuration file.

## Objective

The objective of this practical is to understand:

- What is a Kubernetes Pod
- How to create a Pod using YAML
- How to deploy the Pod using kubectl
- How to check the Pod status
- How to inspect Pod details

## Technology Used

- Kubernetes
- Docker Desktop
- kubectl
- Nginx

## YAML Configuration

The `pod.yaml` file creates an Nginx Pod using the official Nginx container image.

## Commands Used

```bash
kubectl get nodes

kubectl apply -f pod.yaml

kubectl get pods

kubectl describe pod nginx-pod
