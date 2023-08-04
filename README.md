# cron-helm-chart
Contains the generic helm chart that run kubernetes cron job. It is used by Prometheus & Disco project

## Usage

Reference the release of the chart you want to deploy in terraform

```hcl
resource "helm_release" "app" {
  chart     = "https://github.com/DND-IT/cron-helm-chart/archive/v1.0.1.tar.gz"
  ...
}
```
## Requirements 
Compatible with helm3