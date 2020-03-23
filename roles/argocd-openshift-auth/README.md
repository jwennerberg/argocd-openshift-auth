argocd-openshift-auth
=========

Install ArgoCD with argocd-operator v0.0.4 and apply all
neccessary fixes to get OpenShift authentication to work.

NOTE: most of this will not be needed in coming releases of argocd-operator

Role Variables
--------------
Role variables incuding present defaults.

```
ocp_cluster:
  name: crc
  base_domain: testing

argocd:
  namepsace: argocd
  name: argocd
```

License
-------

Apache 2.0
