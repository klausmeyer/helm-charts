# docker-registry-browser

A Helm chart for https://github.com/klausmeyer/docker-registry-browser

## Changelog

see [RELEASENOTES.md](RELEASENOTES.md)

## Usage

```shell
helm repo add klausmeyer https://klausmeyer.github.io/helm-charts/
helm install my-release klausmeyer/docker-registry-browser
```

## Warning

The application isn't doing any versioning yet so this chart uses the `latest` Docker tag by default.
