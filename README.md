# Azure Static Web Apps Web App Review Fixture

This static app is the source for `commentary-dev/commentary-web-app-azure-swa-fixture`.

`staticwebapp.config.json` configures narrow review-environment frame headers:

```json
{
  "globalHeaders": {
    "Content-Security-Policy": "frame-ancestors https://commentary.dev http://localhost:3000 http://localhost:3001"
  }
}
```

Use this fixture when validating deployed previews that can explicitly allow Commentary to embed the app.
