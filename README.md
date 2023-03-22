# Common pipelines

Common pipelines

### Helm

Source: `helm.yml`

Build and publish helm package to repository `oci://ghcr.io/${{ github.repository_owner }}`.

### Docker

Source: `docker.yml`

Build and publish docker image to `ghcr.io/${{ github.repository_owner }}`