# microservices-sandbox-helm-chart

A helm chart for deploying the Microservices Sandbox demo apps to your Kubernetes cluster.

## Pre-Requisites

```
kubectl create secret generic newrelic --from-literal=license_key=<YOUR LICENSE KEY>
```

## Installation

```
helm repo add https://bpschmitt.github.io/microservices-sandbox-helm-chart
helm install microservices-sandbox microservices-sandbox/microservices-sandbox
```