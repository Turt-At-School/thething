# ENSF400A3LionelHasan

# To properly run this lab, the following commands must be ran in order ideally:

1. kubectl apply -f nginx-configmap.yaml
2. kubectl apply -f nginx-dep.yaml
3. kubectl apply -f nginx-svc.yaml
4. kubectl apply -f nginx-ingress.yaml

5. kubectl apply -f app-1-dep.yaml
6. kubectl apply -f app-1-svc.yaml
7. kubectl apply -f app-1-ingress.yaml

8. kubectl apply -f app-2-dep.yaml
9. kubectl apply -f app-2-svc.yaml
10. kubectl apply -f app-2-ingress.yaml


# How Requirements are met

1. **Nginx-dep deployed with 5 replicas with version tag 1.14.2 and exposes 80 :** 