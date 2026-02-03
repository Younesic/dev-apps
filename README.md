# dev-apps

Repo des équipes dev. Contient uniquement un fichier `app.yaml` par app/environnement.

Structure:
- apps/dev/<app>/app.yaml

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
sealedSecret:
  name: app-secret
  encryptedData:
    API_KEY: "REPLACE_WITH_SEALED_VALUE"
    DB_URL: "REPLACE_WITH_SEALED_VALUE"
```

Contenu minimum côté dev :
- `apps/dev/payment/app.yaml`
