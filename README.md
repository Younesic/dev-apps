# dev-apps

Repo des équipes dev. Contient uniquement les définitions d’apps (fichiers YAML) utilisées par l’ApplicationSet.

Structure:
- apps/dev/*.yaml

Exemple:
```yaml
name: payment-service-dev-app-v1
namespace: payment-service-dev
project: payment-service-dev
template: webapp
imageName: nginx
imageTag: "1.27"
replicas: 1
```
