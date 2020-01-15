bazarr
======
Bazarr is a companion application to Sonarr and Radarr. It can manage and download subtitles based on your requirements. You define your preferences by TV show or movie and Bazarr takes care of everything for you.

Current chart version is `0.1.3`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| bazarr.guid | int | `1000` |  |
| bazarr.movies.enabled | bool | `false` |  |
| bazarr.movies.existingClaim | string | `""` |  |
| bazarr.movies.subPath | string | `""` |  |
| bazarr.puid | int | `1000` |  |
| bazarr.tv.enabled | bool | `false` |  |
| bazarr.tv.existingClaim | string | `""` |  |
| bazarr.tv.subPath | string | `""` |  |
| bazarr.tz | string | `"UTC"` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"Always"` |  |
| image.repository | string | `"linuxserver/bazarr"` |  |
| image.tag | string | `"latest"` |  |
| ingress.annotations | object | `{}` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts[0] | string | `"chart-example.local"` |  |
| ingress.paths[0] | string | `"/"` |  |
| ingress.tls | list | `[]` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| persistence.accessModes[0] | string | `"ReadWriteOnce"` |  |
| persistence.enabled | bool | `false` |  |
| persistence.size | string | `"1Gi"` |  |
| persistence.storageClassName | string | `""` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |
| service.port | int | `6767` |  |
| service.type | string | `"ClusterIP"` |  |
| tolerations | list | `[]` |  |
