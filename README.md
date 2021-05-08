# Argo application of applications helm chart

## Installing argoCD

You will first of all need argocd installed on your k8 cluster, if you have already done this you can skip this section

- Install argocd <br />
  ```
  kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
  ```
  
- If you want to run argocd behind an ingress you will need to patch the deployment argocd-server with the following
  ```
  
  ```
