# Personal K8s cluster for learning and homelabing 🏡

### Architecture

- k3s for single node cluster - someday will move to multi node
- metalLB
- traefik as Ingress - comes with k3s
- nvidia-device-plugin to pass the gpu to pods
- fluxcd for GitOps

**TODO**
- properly handle secrets
- cert-manager
- set up monitoring (LGTM stack)


### Setup Instructions

- Install k3s
- Install and configure nvidia gpu pass through
- Install and configure fluxcd



### Apps running
- Sample Go rest api. No real functionality. Just a status endpoint.
    Used mainly for testing out things
- Jellyfin

