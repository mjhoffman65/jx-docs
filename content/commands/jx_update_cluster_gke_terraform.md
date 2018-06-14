---
date: 2018-06-14T13:40:21Z
title: "jx update cluster gke terraform"
slug: jx_update_cluster_gke_terraform
url: /commands/jx_update_cluster_gke_terraform/
---
## jx update cluster gke terraform

Updates an existing kubernetes cluster on GKE using Terraform: Runs on Google Cloud

### Synopsis

Command re-applies the terraform plan in ~/.jx/clusters/ <cluster>/terraform against the specified cluster

```
jx update cluster gke terraform [flags]
```

### Examples

```
  jx update cluster gke terraform
```

### Options

```
  -n, --cluster-name string   The name of this cluster
  -h, --help                  help for terraform
```

### SEE ALSO

* [jx update cluster gke](/commands/jx_update_cluster_gke/)	 - Updates an existing kubernetes cluster on GKE: Runs on Google Cloud

###### Auto generated by spf13/cobra on 14-Jun-2018