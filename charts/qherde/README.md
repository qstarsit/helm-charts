# QHerde Helm Chart

A simple Helm chart to deploy QHerde on a Kubernetes cluster.

Two variables are required to be set: `rapidapi_host` and `rapidapi_key`. For example:

```sh
# Note that the key is base64 encoded
helm install demo --set configMap.rapidapi_host=somehost.rapidapi.com --set secret.rapidapi_key=c29tZWFwaWtleQ==  .
```
