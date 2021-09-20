# Traefik Helm Chart

- traefik · traefik/traefik (https://artifacthub.io/packages/helm/traefik/traefik)

## Get Repo Info

```console
$ helm repo add traefik https://helm.traefik.io/traefik
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `traefik`:

```console
$ helm install traefik --version <version> traefik/traefik -f values.yaml
$ helm apply -f dashboard.yaml
$ helm apply -f middleware.yaml
```

## Uninstalling the Chart

To uninstall/delete the traefik deployment:

```console
$ helm delete traefik
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

