# install Gitea on OpenShift with custom configuration

1. Use this documentation to install Gitea via Operator: https://github.com/rhpds/gitea-operator

2. Apply `configmap.yaml`

3. Apply `gitea-instance.yaml`

4. Create SSH Ticket `oc create secret generic my-ssh-secret --from-file=ssh-privatekey=ssh_id`

5. Create ArgoCD instance `argo-instance.yaml`
