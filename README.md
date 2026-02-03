# dev-apps

Repo des équipes dev. Contient uniquement les définitions d’apps (fichiers YAML) utilisées par l’ApplicationSet.

Structure:
- apps/dev/*.yaml

Exemple:
```yaml
name: payment-service-dev-app-v1
namespace: payment-service-dev
project: payment-service-dev
repoURL: https://github.com/Younesic/platform-gitops.git
revision: main
appPath: apps/templates/hello
```
