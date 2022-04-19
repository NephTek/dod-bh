# dod-bh
DevOps Days Birmingham Stack 

You will need to edit out most refernces to nephtek or nephtek.com for your own URL (feel free to make one up, it does not have to be valid).

Sections that contain .ipynb are Jupyter Notebooks intended to be ran in Jupyter. Or you can extract the code from them if you wish.

Recommended install order in fresh cluster:\
dnsmasq\
monitoring\
cert-manager\
ingress\
postgres\
openldap\
kube-oidc-proxy\
oauth2-proxy\
keycloak\
logging

This is part of what we have dubbed "IDOP" or "Internal DevOps Platform". It allows for completely local development on a kubernetes cluster that mimics an enterprise environment.
