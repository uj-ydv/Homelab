# Homelab
Welcome to the Homelab repository! This repository contains the setup and configuration files for running a K3s single-node cluster with various self-hosted applications and services. Started this lab for getting my head around kubernetes, I kinda like it now and in the process of migrating the homelab from docker to kubernetes.

### **Expose Apps via Cloudflare Tunnel(Optional)**
You can securely expose your applications to the internet using Cloudflare Tunnel, which ensures that your services are accessible from anywhere without opening ports on your router.

I don't expose all applications, but only few of them.
To-Do : Configuration setup/setting

### **Applications** - To-Do
- Hoarder
- Obsidian
- Code Server
- Mealie
- Vaultwarden(Do i really want to do it ????)

### **Storage Setup**
Since I'm operating a single-node cluster for my homelab, I am utilizing local storage for my storage needs. This approach simplifies my setup, as I don't require the complexities of a multi-node distributed storage solution. For now, local storage remains the most practical and performant solution, considering the scale and nature of my homelab environment. However, I would continue to evaluate other storage solutions as my Kubernetes setup evolves.

### Secrets Management
I'm currently using .env files for variables and secret. Plan on integrating Secret management solution.

### **Ingress Controller**
Traefik

### **Managing Applications**


### **Future Roadmap**
- More Apps(Ofcourse)
- Gitops : Either Argo or Flux(already have a repo with argo kustomization setup while playing around earlier)
- Secrets Management : Infiscal/Vault/SOPS?
- Service Mesh(Only play around and not really deploy)
- Kubernetes : Moving to Multi-Node Cluster