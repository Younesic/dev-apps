# dev-apps

Repo des équipes dev. Contient uniquement un fichier `config.yaml` par app/environnement.

Structure:
- apps/dev/<app>/config.yaml

Exemple:
```yaml
name: payment-service-dev-app-v1
namespace: payment-service-dev
project: payment-service-dev
imageName: nginx
imageTag: "1.27"
replicas: 1
config:
  APP_MESSAGE: "hello payment dev"
  APP_COLOR: "blue"
  FEATURE_X_ENABLED: "true"
```

Contenu minimum côté dev :
- `apps/dev/payment/config.yaml`
