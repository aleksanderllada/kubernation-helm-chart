# Kubernation Helm Chart

This chart is useful for deploying Kubernation.

## Configuration

|             Parameter               |            Description                   |                    Default                     |
|-------------------------------------|------------------------------------------|------------------------------------------------|
| `domain`                            | Domain for the ingress resource          |                                                |
| `dashboard.replicas`                | The number of replicas for the dashboard | `1`                                            |
| `dashboard.image`                   | The image of the dashboard w/ tag        | `aleksanderllada/kubernation-dashboard:latest` |
| `dashboard.memory.min`              | Requested memory for the dashboard       | `64Mi`                                         |
| `dashboard.memory.max`              | Limit memory for the dashboard           | `256Mi`                                        |
| `dashboard.cpu.min`                 | Requested cpu for the dashboard          | `50m`                                          |
| `dashboard.cpu.max`                 | Limit cpu for the dashboard              | `200m`                                         |
| `api.replicas`                      | The number of replicas for the api       | `1`                                            |
| `api.image`                         | The image of the api w/ tag              | `aleksanderllada/kubernation-api:latest`       |
| `api.memory.min`                    | Requested memory for the api             | `64Mi`                                         |
| `api.memory.max`                    | Limit memory for the api                 | `256Mi`                                        |
| `api.cpu.min`                       | Requested cpu for the api                | `50m`                                          |
| `api.cpu.max`                       | Limit cpu for the api                    | `200m`                                         |
