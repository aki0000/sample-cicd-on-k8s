# sample-cicd-on-k8s

``` /bin/bash
# Deploy OpenShift GitOps
oc apply -f openshift-gitops/

# Deploy ArgoCD
oc apply -f argocd/

# Deploy sample application by ArgoCD
oc apply -f argocd/applocations
```
