# My [Helm](https://helm.sh) Charts

This repository contains [Helm](https://helm.sh) charts for various projects

* [Application 1](charts/app1/)
* [Application 2](charts/app2/)

## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add my-helm-charts https://www.markalston.net/my-helm-charts

Install Application 1:

    helm install test my-helm-charts/app1

Install Application 2:

    helm install test my-helm-charts/app2
