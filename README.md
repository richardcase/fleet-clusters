# fleet-clusters

Add this to the Rancher Manager cluster

```yaml
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: manifests
  namespace: fleet-local
spec:
  repo: https://github.com/richardcase/fleet-clusters
```
