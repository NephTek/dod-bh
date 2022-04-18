# dod-bh
DevOps Days Birmingham Stack 

Recommended install order in fresh cluster:
dnsmasq
monitoring
cert-manager
ingress
postgres
openldap
kube-oidc-proxy
oauth2-proxy
keycloak
logging

This is part of what we have dubbed "IDOP" or "Internal DevOps Platform". It allows for completely local development on a kubernetes cluster that mimics an enterprise environment.
