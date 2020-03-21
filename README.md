# Factorio

This helm chart deploys a factoriotools/factorio docker container to K8s.

It also supports backup and restore of saves and mods via s3.

Deploy it via:

```
helm install .
```

## Values

This chart is configurable via values. Check out the default [values.yaml](values.yaml) 
and deploy via `helm install . --name factorio -f values.yaml`

