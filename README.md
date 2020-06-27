# Apache Superset on Staroid ⭐️

[Apache Superset](https://github.com/apache/incubator-superset) on staroid

[![Run](https://staroid.com/api/run/button.svg)](https://staroid.com/api/run)

## Development

Run locally with [skaffold](https://skaffold.dev) command.

```
$ skaffold dev -f .staroid/skaffold.yaml --port-forward -p minikube
```

and browse `http://localhost:8088`
