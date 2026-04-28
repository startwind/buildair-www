# buildair.cloud — Website

Static marketing website for [buildair.cloud](https://buildair.cloud).

## Local development

```bash
docker compose up
```

The site is available at **http://localhost:8080**.

## Deployment

The site is deployed via [Buildair](https://buildair.cloud) using `buildair.yml`. It is served by nginx and exposed at `https://web.<project-id>.preview.buildair.cloud`.
