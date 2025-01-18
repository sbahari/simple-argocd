Simple ArgoCD Project

Project Requirements

- Kind (Kubernetes-in-Docker)
- Terraform CLI
- Helm
- Kustomize

Quick Start

Clone Repository
$ git clone git@github.com:sbahari/simple-argocd.git

Create Kubernetes Cluster with Kind
$ kind create cluster

Install ArgoCD with Terraform and Helm
$ cd terraform
$ terraform init
$ terraform apply

Deploy ArgoCD Manifest and Sample Kube Deployment
$ kustomize build argocd-fleets/overlays/develop