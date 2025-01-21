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

$ cd terraform <br />
$ terraform init <br />
$ terraform apply <br />

Create Project with name argocd On ArgoCD UI

Deploy ArgoCD Manifest and Sample Kube Deployment
$ kustomize build argocd-fleets/overlays/develop
