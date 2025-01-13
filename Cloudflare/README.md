# Setup

Insert your token in the .env

Generate the Configmap
```
kubectl create configmap -n cloudflare cloudflared-env --from-env-file=.env --dry-run=client -o yaml
kubectl create configmap -n cloudflare cloudflared-env --from-env-file=.env
```

Execute the manifest files
```
kubectl apply manifest.yaml
```