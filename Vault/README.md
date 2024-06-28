# expose vault ui/api
kubectl port-forward service/vault --address=0.0.0.0 8200:8200 -n vault
