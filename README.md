# kubernetes-all

## General Topics

* Kubectl Cheat Sheet
https://www.digitalocean.com/community/cheatsheets/getting-started-with-kubectl-a-kubectl-cheat-sheet?status=moved_permanently 

* Programmatically generated handy kubectl aliases. 
https://ahmet.im/blog/kubectl-aliases/

## K8s CICD

How to deploy to k8s by Jenkins pipeline as code. Forked from Slalom Dojo:
https://github.com/jimmycgz/cicd-k8s 

Watch the video for how doesn't Google engineers do with jenkins-k8s:
https://cloud.google.com/solutions/jenkins-on-kubernetes-engine

## EKS
Build EKS from Zero by Terraform 

https://aws.amazon.com/blogs/startups/from-zero-to-eks-with-terraform-and-helm/ 

We can also leverage the existing module in Terraform but I prefer the above way.

Detailed doc about EKS:
https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html

## Universal Solution to Build K8s across Hybrid Platforms

Terraform => Rancher => Helm => Istio

1. Build Rancher by Terraform

Option #1: Use Terraform service provider of rancher https://www.terraform.io/docs/providers/rancher/index.html

Option #2: Use Rancher OS Image https://rancher.com/docs/rancher/v2.x/en/quick-start-guide/deployment/


2. Build K8s cluster by Rancher (on VM, Vagrant, EKS, AKS, GKS)
To be documented

3. Use Helm and Istio to wrap up service mesh at abstract level
To be documented
